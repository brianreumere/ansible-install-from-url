# ansible-role-install-from-url

## Variables

- `name`: A unique name for the package
- `version`: The version of the package to install
- `download_url`: The URL to download the package from
- `checksum`: The checksum of the downloaded file (formatted as expected by the [`get_url` module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/get_url_module.html)
- `unarchive`: Whether the downloaded file needs to be unarchived
- `install_cmd`: The command to run to install the package
