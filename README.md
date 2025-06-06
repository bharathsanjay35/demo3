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


<build>
 <plugins>
 <plugin>
 <artifactId>maven-jar-plugin</artifactId>
 <version>3.1.0</version>
 <configuration>
 <archive>
 <manifest>
 <addClasspath>true</addClasspath>
 <mainClass>com.multit.App</mainClass> <!-- Replace with main class
 </manifest>
 </archive>
 </configuration>
 </plugin>
 </plugins>
 </build>
  -->
