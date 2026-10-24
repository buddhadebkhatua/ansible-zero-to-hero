Ansible Zero to Hero — 30-Day Playbook

Beginner → Advanced → Production-ready automation | Hands-on labs | GitHub portfolio | Interview preparation

This 30-day roadmap is designed to help you learn Ansible practically and apply it to real infrastructure administration, Linux automation, cloud operations, and DevOps workflows.

The goal is not just to memorize Ansible commands. By Day 30, you should be able to automate Linux server administration, manage configuration across multiple servers, deploy applications, troubleshoot failures, and build a portfolio of reusable Ansible playbooks.
What you will build


1. Ansible fundamentals

Inventory, ad-hoc commands, YAML, playbooks, variables, facts, loops, conditions, and handlers.


2. Linux infrastructure automation

Users, groups, packages, services, permissions, firewalls, storage, patching, and security hardening.


3. Advanced and enterprise Ansible

Roles, templates, Vault, collections, error handling, reusable automation, and CI/CD integration.



4. Final production-style project

Build a reusable automation repository for Linux configuration, security compliance, application deployment, and reporting.

30-day learning roadmap

Day 1: Introduction to Ansible
Topics: What Ansible is, architecture, control node vs managed nodes, agentless automation, use cases.
Lab: Install Ansible and verify ansible --version.

Day 2: Lab setup and SSH authentication
Topics: Install Ansible on Rocky Linux or Ubuntu; configure SSH keys, sudo access, and Python on managed nodes.
Lab: Connect to two Linux servers without an SSH password.

Day 3: Inventory management
Topics: Static inventory, host groups, child groups, host variables, group variables, INI and YAML formats.
Lab: Create dev, test, and production inventory groups.

Day 4: Ad-hoc commands
Topics: Use ping, command, shell, copy, file, service, package, and setup modules.
Lab: Check uptime, disk space, memory, and service status across servers.

Day 5: Your first playbook
Topics: Playbook structure, YAML syntax, plays, tasks, module arguments, hosts, become, and execution.
Lab: Write a playbook to install and start Nginx.

Day 6: Variables and precedence
Topics: Play variables, inventory variables, group_vars, host_vars, registered variables, and precedence.
Lab: Use one playbook with different settings for dev and production.

Day 7: Facts and system discovery
Topics: Gather facts, inspect ansible_facts, use setup, and select tasks based on operating system.
Lab: Generate a report containing hostname, OS, IP address, CPU, and memory.

Day 8: Conditionals
Topics: when, comparisons, Boolean conditions, fact-based decisions, and registered results.
Lab: Install packages conditionally on Rocky Linux and Ubuntu.

Day 9: Loops and lists
Topics: loop, dictionaries, lists, loop_control, and iterating over users and packages.
Lab: Create multiple users and install multiple packages in one playbook.

Day 10: Handlers and idempotency
Topics: notify, handlers, changed status, idempotent modules, and safe repeated execution.
Lab: Update an Nginx configuration and restart only when it changes.

Day 11: Files, directories, and permissions
Topics: file, copy, fetch, lineinfile, blockinfile, ownership, modes, and symlinks.
Lab: Deploy a standard Linux directory structure and configuration files.

Day 12: Users, groups, and sudo
Topics: user and group modules, SSH authorized keys, sudoers management, and access controls.
Lab: Provision a standard administrator account with restricted sudo access.

Day 13: Package and service management
Topics: dnf, apt, package, service, systemd, service enablement, and package versions.
Lab: Configure and validate essential Linux services.

Day 14: Jinja2 templates
Topics: Templates, variables, filters, conditionals inside templates, and template module.
Lab: Generate different Nginx configurations from a single template.

Day 15: Roles and reusable automation
Topics: Role directory structure, defaults, vars, tasks, handlers, templates, and files.
Lab: Build a reusable Nginx role.

Day 16: Ansible Vault
Topics: Encrypt files and variables, vault IDs, vault passwords, and secure secret handling.
Lab: Deploy an application using encrypted credentials.

Day 17: Error handling and validation
Topics: failed_when, changed_when, ignore_errors, block, rescue, always, and assert.
Lab: Handle deployment failures and run post-deployment validation.

Day 18: Tags and selective execution
Topics: Task tags, role tags, --tags, --skip-tags, --start-at-task, and --list-tasks.
Lab: Run only the configuration, security, or validation part of a playbook.

Day 19: Dynamic inventories
Topics: Inventory plugins, cloud inventory concepts, host discovery, and inventory verification.
Lab: Discover cloud instances dynamically or build a small custom inventory plugin lab.

Day 20: Collections and module discovery
Topics: Collections, FQCNs, ansible-galaxy, requirements.yml, documentation, and community modules.
Lab: Install a collection and use a module from its fully qualified collection name.

Day 21: Linux security hardening
Topics: SSH configuration, firewall rules, permissions, audit settings, package updates, and compliance checks.
Lab: Apply a baseline security role and verify the resulting configuration.

Day 22: Storage and filesystem automation
Topics: Filesystem and mount modules, disk discovery, LVM concepts, fstab management, and validation.
Lab: Automate a lab filesystem mount with safeguards against accidental data loss.

Day 23: Scheduled jobs and system maintenance
Topics: cron, systemd timers, patching, reboot workflows, maintenance windows, and post-checks.
Lab: Build a controlled patching playbook with reboot detection and service validation.

Day 24: Application deployment
Topics: Artifact delivery, configuration templates, service units, handlers, health checks, and rollback planning.
Lab: Deploy a sample web application from configuration to service validation.

Day 25: AWS automation fundamentals
Topics: AWS credentials and IAM permissions, boto3 prerequisites, cloud collections, EC2 discovery, and tagging.
Lab: Automate a safe EC2 inventory or inspect existing instances using least-privilege credentials.

Day 26: Ansible with Docker and Kubernetes
Topics: Docker host configuration, container deployment, Kubernetes collections, kubeconfig security, and cluster automation concepts.
Lab: Deploy a container or manage a lab Kubernetes resource using Ansible.

Day 27: Ansible with Jenkins and Git
Topics: Git-based playbooks, Jenkins pipeline stages, linting, check mode, approvals, and deployment credentials.
Lab: Create a pipeline that validates playbooks before running an approved deployment.

Day 28: Testing, linting, and troubleshooting
Topics: ansible-lint, syntax-check, --check, --diff, verbosity, debug, molecule concepts, and failure analysis.
Lab: Test and troubleshoot a reusable role before deploying it.

Day 29: Enterprise project integration
Topics: Combine inventories, roles, Vault, validation, logging, documentation, and controlled execution.
Lab: Build a complete Linux server provisioning and compliance automation project.

Day 30: Capstone, review, and interview
Topics: Production design, operational safeguards, code review, troubleshooting scenarios, and interview questions.
Lab: Demonstrate the complete project and publish your final GitHub documentation.
