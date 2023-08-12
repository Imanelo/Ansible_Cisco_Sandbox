
# Practice Ansible with Cisco Sandbox 

# Guide

**Step 1: Create a playbook**

$ touch play_gather-facts.yml

**Step 2: Run the playbook**

$ ansible-playbook play_gather-facts.yml -i inventories/dev/

**Step 3: Add reporting tasks to the playbook**

We will now edit the playbook to create a folder to store our device reports. We use a Jinja2 template to dynamically generate a report file for each device. Then we consolidate each individual device report into a single report.

**Step 4: Create the Jinja2 template referenced in Step 3**

$ touch ios_report.j2

**Step 5: Run the updated playbook**

**Step 6: View the rendered reports**

#Project Structure
