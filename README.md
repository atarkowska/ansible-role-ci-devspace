OME Devspace 2
==============

Provision OME developer devspace


Role Variables
--------------

All variables are optional, see `defaults/main.yml` for the full list

- `snoopy_dir_path`: path to ssh keys and gitconfig like "/path/to/snoopy_keys". See devspace README for more details.

- `devspace_git_repo`:  devspace git source
- `devspace_git_repo_version`: github branch or tag

- `devspace_git_update`: retrieve new revisions from the origin git repository
- `devspace_git_force`: reset any modified files

- `devspace_omero_branch`: openmicroscopy.git branch

- `devspace_jenkins_username`: jenkins username
- `devspace_jenkins_password`: jenkins password

- `devspace_jenkins_nginx_username`: basic HTTP authentication username
- `devspace_jenkins_nginx_password`:  password


Example
-------

TODO


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
