# Ansible - Deploy Wordpress with SSL

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

> This was a lab suggested by [Umbler](https://umbler.com/) to deploy an [Worpress](https://wordpress.org/) server using IoC as [Ansible](https://www.ansible.com/).

This is an script where the main objective is to build a Docker service for Wordpress-FPM, Nginx and Mysql.

## Demo

An application deploy can be found hosted at [AWS](https://aws.amazon.com/). 
* Link to access: [Wordpress-FPM](https://umblerchallange.tk/).

## :pushpin: Table of Contents

* [Technologies](#-technologies)
* [Installation](#construction_worker-installation)
* [Getting Started](#runner-getting-started)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [License](#closed_book-license)

## 💻 Technologies

This project was developed with the following technologies:

- [Ansible](https://www.ansible.com/)
- [Docker](https://www.docker.com/)
- [Docker-Compose](https://docs.docker.com/compose/)
- [Docker Hub](https://hub.docker.com/)
- [Let’s Encrypt](https://letsencrypt.org/)
- [Mysql](https://www.mysql.com/)
- [Nginx](https://www.nginx.com/)
- [PHP](https://www.php.net/)
- [Python](https://www.python.org/)
- [Python-Pip](https://pypi.org/project/pip/)
- [Wordpress](https://wordpress.org/)

## :construction_worker: Installation

**You need to install [Git](https://git-scm.com/) and [Ansible](https://www.ansible.com/) first, then in order to clone the project via HTTPS, run this command:**

```
git clone https://github.com/viniciusbmello/ansible_docker_wordpress.git
```

## :runner: Getting Started

Run the following command to run the playbook:

```
ansible-playbook -i hosts playbook.yml
```

After done, you can open [umblerchallange.tk](https://umblerchallange.tk/).

## :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [Ansible - Deploy Wordpress with SSL](https://github.com/viniciusbmello/ansible_docker_wordpress/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**!

## :closed_book: License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
