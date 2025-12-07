# My Own Custom Ansible Collection: my_own_namespace.yandex_cloud_elk

This repository contains a custom Ansible Collection designed to manage specific configuration tasks related to Yandex Cloud ELK deployment setup.

## Installation

This collection uses a custom module (`file_creator`). To use it, you must install the collection from the built artifact (tar.gz file).

1.  **Download the archive:** Download the `my_own_namespace-yandex_cloud_elk-1.0.0.tar.gz` file (e.g., from GitHub Releases).
2.  **Install via Ansible Galaxy:**
    ```bash
    ansible-galaxy collection install /path/to/my_own_namespace-yandex_cloud_elk-1.0.0.tar.gz
    ```

## Collection Contents

### Role: `file_setup`
This role utilizes the custom module `file_creator` to ensure specific files exist with defined content.

*   **FQCN Example:** `my_own_namespace.yandex_cloud_elk.file_setup`

### Custom Module: `file_creator`
A custom module included in this collection responsible for idempotently creating or updating files on managed hosts.

## Version
**Current Version:** 1.0.0 (Tagged in Git)

---
*Created by Dmitriy-py for the Ansible Deployment Course.*
