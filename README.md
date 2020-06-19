# Ansible Collection: ansible.windows

[![Run Status](https://api.shippable.com/projects/5e4d952ef7b7100007bcf1a1/badge?branch=master)](https://app.shippable.com/github/ansible-collections/ansible.windows/dashboard/jobs)
[![codecov](https://codecov.io/gh/ansible-collections/ansible.windows/branch/master/graph/badge.svg)](https://codecov.io/gh/ansible-collections/ansible.windows)


This repo hosts the `ansible.windows` Ansible Collection.

The collection includes the core plugins supported by Ansible to help the management of Windows hosts.


<!--start requires_ansible-->
## Ansible version compatibility

This collection has been tested against following Ansible versions: **>=2.10**.

Plugins and modules within a collection may be tested with only specific Ansible versions.
A collection may contain metadata that identifies these versions.
PEP440 is the schema used to describe the versions of Ansible.
<!--end requires_ansible-->


## Included content

<!--start collection content-->
### Filter plugins
Name | Description
--- | ---
ansible.windows.quote|Quotes argument(s) for the various shells in Windows command processing.

### Modules
Name | Description
--- | ---
[ansible.windows.win_acl](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_acl_module.rst)|Set file/directory/registry permissions for a system user or group
[ansible.windows.win_acl_inheritance](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_acl_inheritance_module.rst)|Change ACL inheritance
[ansible.windows.win_certificate_store](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_certificate_store_module.rst)|Manages the certificate store
[ansible.windows.win_command](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_command_module.rst)|Executes a command on a remote Windows node
[ansible.windows.win_copy](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_copy_module.rst)|Copies files to remote locations on windows hosts
[ansible.windows.win_dns_client](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_dns_client_module.rst)|Configures DNS lookup on Windows hosts
[ansible.windows.win_domain](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_domain_module.rst)|Ensures the existence of a Windows domain
[ansible.windows.win_domain_controller](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_domain_controller_module.rst)|Manage domain controller/member server state for a Windows host
[ansible.windows.win_domain_membership](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_domain_membership_module.rst)|Manage domain/workgroup membership for a Windows host
[ansible.windows.win_dsc](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_dsc_module.rst)|Invokes a PowerShell DSC configuration
[ansible.windows.win_environment](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_environment_module.rst)|Modify environment variables on windows hosts
[ansible.windows.win_feature](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_feature_module.rst)|Installs and uninstalls Windows Features on Windows Server
[ansible.windows.win_file](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_file_module.rst)|Creates, touches or removes files or directories
[ansible.windows.win_find](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_find_module.rst)|Return a list of files based on specific criteria
[ansible.windows.win_get_url](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_get_url_module.rst)|Downloads file from HTTP, HTTPS, or FTP to node
[ansible.windows.win_group](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_group_module.rst)|Add and remove local groups
[ansible.windows.win_group_membership](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_group_membership_module.rst)|Manage Windows local group membership
[ansible.windows.win_hostname](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_hostname_module.rst)|Manages local Windows computer name
[ansible.windows.win_optional_feature](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_optional_feature_module.rst)|Manage optional Windows features
[ansible.windows.win_owner](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_owner_module.rst)|Set owner
[ansible.windows.win_package](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_package_module.rst)|Installs/uninstalls an installable package
[ansible.windows.win_path](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_path_module.rst)|Manage Windows path environment variables
[ansible.windows.win_ping](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_ping_module.rst)|A windows version of the classic ping module
[ansible.windows.win_reboot](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_reboot_module.rst)|Reboot a windows machine
[ansible.windows.win_reg_stat](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_reg_stat_module.rst)|Get information about Windows registry keys
[ansible.windows.win_regedit](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_regedit_module.rst)|Add, change, or remove registry keys and values
[ansible.windows.win_service](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_service_module.rst)|Manage and query Windows services
[ansible.windows.win_service_info](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_service_info_module.rst)|Gather information about Windows services
[ansible.windows.win_share](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_share_module.rst)|Manage Windows shares
[ansible.windows.win_shell](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_shell_module.rst)|Execute shell commands on target hosts
[ansible.windows.win_stat](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_stat_module.rst)|Get information about Windows files
[ansible.windows.win_tempfile](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_tempfile_module.rst)|Creates temporary files and directories
[ansible.windows.win_template](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_template_module.rst)|Template a file out to a remote server
[ansible.windows.win_updates](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_updates_module.rst)|Download and install Windows updates
[ansible.windows.win_uri](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_uri_module.rst)|Interacts with webservices
[ansible.windows.win_user](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_user_module.rst)|Manages local Windows user accounts
[ansible.windows.win_user_right](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_user_right_module.rst)|Manage Windows User Rights
[ansible.windows.win_wait_for](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_wait_for_module.rst)|Waits for a condition before continuing
[ansible.windows.win_whoami](https://github.com/ansible-collections/ansible.windows/blob/master/docs/ansible.windows.win_whoami_module.rst)|Get information about the current user and process

<!--end collection content-->


## Installation and Usage

### Installing the Collection from Ansible Galaxy

Before using the Windows collection, you need to install it with the `ansible-galaxy` CLI:

    ansible-galaxy collection install ansible.windows

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:

```yaml
collections:
- name: ansible.windows
```


## Testing and Development

If you want to develop new content for this collection or improve what's already here, the easiest way to work on the collection is ot clone it into one of the configured [`COLLECTIONS_PATHS`](https://docs.ansible.com/ansible/latest/reference_appendices/config.html#collections-paths), and work on it there.


### Generating plugin docs

Currently module documentation is generated manually using
[add_docs.py](https://github.com/ansible-network/collection_prep/blob/master/add_docs.py). This should be run whenever
there are any major doc changes or additional plugins have been added to ensure a docpage is viewable online in this
repo. The following commands will run the doc generator and create the updated doc pages under [docs](docs).

```bash
# This is the path to the ansible.windows checkout
COLLECTION_PATH=~/ansible_collections/ansible/windows

cd /tmp
git clone https://github.com/ansible-network/collection_prep.git
cd collection_prep
python add_docs.py -p "${COLLECTION_PATH}"
```


### Testing with `ansible-test`

The `tests` directory contains configuration for running sanity and integration tests using [`ansible-test`](https://docs.ansible.com/ansible/latest/dev_guide/testing_integration.html).

You can run the collection's test suites with the commands:

    ansible-test sanity --docker
    ansible-test windows-integration --docker


## Publishing New Version

The current process for publishing new versions of the Windows Core Collection is manual, and requires a user who has access to the `ansible` namespace on Ansible Galaxy and Automation Hub to publish the build artifact.

* Update the CHANGELOG:
  * Make sure you have [`antsibull-changelog`](https://pypi.org/project/antsibull-changelog/) installed.
  * Make sure there are fragments for all known changes in `changelogs/fragments`.
  * Run `antsibull-changelog release`
* Update `galaxy.yml` with the new `version` for the collection.
* Create a release in GitHub to tag the commit at the version to build.
* Run the following commands to build and release the new version on Galaxy:
     ```
     ansible-galaxy collection build
     ansible-galaxy collection publish ./ansible-windows-$VERSION_HERE.tar.gz
     ```

After the version is published, verify it exists on the [Windows Core Collection Galaxy page](https://galaxy.ansible.com/ansible/windows).


## More Information

For more information about Ansible's Windows integration, join the `#ansible-windows` channel on Freenode IRC, and browse the resources in the [Windows Working Group](https://github.com/ansible/community/wiki/Windows) Community wiki page.


## License

GNU General Public License v3.0 or later

See [COPYING](COPYING) to see the full text.
