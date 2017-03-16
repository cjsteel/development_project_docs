# creating ansible projects.md

## Ansible development system setup

### Requirements

#### Ansible environment

* miniconda
* ansible conda environment(s)
### git stuff
* git
* mr
### testing stuff
* virtualbox
* vagrant
## Project structure
Example directory structure
```shell
~/projects/ansible/roles/freesurfer
```
### dir variables
```shell
project_root="$HOME/projects/ansel"
project_type=tests                  # ansible
project_sub_type=ws                 # role
project_name=automa                 # freesurfer
```
### ensure for structure
```shell
mkdir -p $project_root/$project_type/$project_sub_type/$project_name
echo $project_root/$project_type/$project_sub_type/$project_name
```

### clone this document

```shell
cd $project_root
git clone git@github.com:cjsteel/development_project_docs.git

## adding project parts

### Criteria
Each project and each project sponsor will have different needs So you want to consider the following:

* We want to be as open as possible 
* We want to keep some information private
* We want to publish what we can
* that some parts can be reused for other types of projects, what to keep private 

### Add project templates

```shell
cd $project_root/$project_type/$project_sub_type
git clone git@github.com:cjsteel/ansible-project-templates.git
```

