# Drupal 8/9/10 Module Development Course

## Course Description

This course will cover all the basics to understand how Drupal's tools work and how to use them effectively.

This course is designed for people with basic knowledge of Drupal 8/9/10 who want to start developing their own modules. By the end of the course, you will have the foundational knowledge needed to search for solutions to specific problems online, understand the answers, and apply them effectively.

The course is built on Drupal's core principles to ensure compatibility with:
- **Drupal 8** (version 8.7.7 and higher)
- **Drupal 9** (all versions)
- **Drupal 10**

We will explore how to customize Drupal's appearance in the **theming section** and adapt it to our needs. While Drupal is very flexible, its complexity can sometimes be challenging.

> **Note**: This course does not teach PHP programming. Prior knowledge of PHP is required.

### Why Take This Course?

- It's one of the most comprehensive Drupal development courses available on Udemy.
- Access to all course code and databases during and after the course.
- Taught by a Drupal backend developer with over a decade of experience (since Drupal 6).

### Topics Covered

1. Creating controllers to build custom pages.
2. Developing custom services and utilizing existing ones.
3. Creating custom templates.
4. Following best practices for service injection.
5. Using Drupal's configuration system.
6. Building custom forms.
7. Altering existing forms.
8. Writing database queries.
9. Working with entities and commonly used functions.
10. Developing custom blocks with additional configurations.
11. Creating menu items.
12. Understanding the permission and access system.

## Who Is This Course For?

- Beginner developers.
- Developers looking to explore Drupal.
- Drupal site builders who want to start developing.
- Web designers and themers.

## Requirements

### Mandatory:
- Basic knowledge of **PHP**.
- Basic to intermediate knowledge of **Drupal 8/9/10**.
- Basic understanding of **HTML**.

### Recommended:
- Familiarity with **Object-Oriented Programming (OOP)** in PHP.
- Experience using an **IDE** (e.g., NetBeans, PhpStorm).
- Knowledge of **Twig**.

### About the Instructor

**Borja Vicente Cespedes**  
*Drupal Architect and Developer*
- Udemy page: https://nisum.udemy.com/user/borja-vicente-2/

---

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/shaal/ddev-gitpod)

# ddev + Gitpod
## Set up a full Drupal dev environment in a browser

This project demonstrates a complete Drupal 9 development environment, utilizing ddev and Gitpod, through your browser.

## Video Demo

Watch a 5 minutes walkthrough video:

<a href="http://www.youtube.com/watch?v=ifk5dF6rGy0"><img src="https://user-images.githubusercontent.com/22901/107867673-c6fc7080-6e4a-11eb-81c9-542cd779026b.png" width=300 alt="Setup a full Drupal dev environment in a browser"></a>

## Prerequisites:
1. [Sign up for gitpod.io](https://gitpod.io/login)

## Try it out:
1. Click on the following link
  https://gitpod.io/#https://github.com/elbercastillomesa/udemy-drupal10
1. Your environment is being prepared, wait about 40 seconds (A splash screen will appear)
1. VScode IDE will be displayed, a few seconds later you will see Umami demo.
1. Run in terminal `ddev xdebug on`
1. Open VScode's debugger, place a new breakpoint in `web/index.php`
1. Open your website's URL in a browser.
1. :tada:

## Do you like PhpStorm instead of Theia or VScode?
1. Open a bash window at the bottom
2. `.ddev/run-phpstorm.sh`

## How does it work?
1. Gitpod - development environment based on Docker
    1. [.gitpod.yml](https://github.com/shaal/ddev-gitpod/blob/main/.gitpod.yml)
        1. Defines the main docker image this environment is built on - `.gitpod.Dockerfile`
        1. Run prebuild commands:
            1. Start ddev
            1. Run `composer install`
            1. Install Umami demo website
    1. [.gitpod.Dockerfile](https://github.com/shaal/ddev-gitpod/blob/main/.gitpod.Dockerfile)
        1. Set base image to Gitpod's `workspace-full` ([link](https://github.com/gitpod-io/workspace-images/tree/master/full))
        1. Install ddev using brew
1. ddev - ridiculously simple setup for complex development environments, allows developers working locally or working with Gitpod in the cloud.
    1. [.ddev/config.yaml](https://github.com/shaal/ddev-gitpod/blob/main/.ddev/config.yaml) - main ddev (default) configuration, can be generated by running `ddev config`

## Thank you
- [@shaal](https://github.com/shaal/) for creating this project.
- [@rfay](https://github.com/rfay) for your endless patience and relentless support that made this project possible.

### Persistent Storage:
* Gitpod backs up the state of the `/workspace/` folder between workspace starts, so that you can revisit them later. Attention: Files in other locations will not be saved!
* [Additional Storage Solutions](https://www.gitpod.io/docs/self-hosted/latest/install/storage)
