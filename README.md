# demo3
abcd
<br>efgh</br>
<!--
---
- name: Deploy JAR
  hosts: local
  become: true

  tasks:
    - name: Copy JAR file
      copy:
        src: /mnt/c/ProgramData/Jenkins/.jenkins/workspace/your-job/target/your-app.jar
        dest: /home/your-username/ansible-lab/app.jar
        mode: '0755'

    - name: Run JAR file
      shell: nohup java -jar /home/your-username/ansible-lab/app.jar > app.log 2>&1 &
  -->
