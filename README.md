```
> Hi there 👋 Welcome to my GitHub! I'm Lalit Kumar, a Junior DevOps Engineer.
```

 > aboutMe.js


```javascript
pipeline {
    agent any

    environment {
        NAME = 'Lalit Kumar'
        ROLE = 'Junior DevOps Engineer | Cloud Enthusiast ☁️'
        LOCATION = 'Gurugram, India'
        MOTTO = 'Automate Everything. Scale Freely. Monitor Continuously.'
    }

    stages {
        stage('👨‍💻 About Me') {
            steps {
                echo "Hey there! I'm ${NAME}, a passionate ${ROLE} from ${LOCATION}."
                echo "🏁 Motto: ${MOTTO}"
            }
        }

        stage('🧠 Skills') {
            steps {
                echo '🔧 Tools & Technologies:'
                echo '🖥️  OS: Linux (Ubuntu, RHEL)'
                echo '🐳  Containers: Docker'
                echo '⚙️  CI/CD: Jenkins'
                echo '📦  IaC: Ansible, Terraform'
                echo '☁️  Cloud: AWS (EC2, S3, VPC, IAM)'
                echo '🔗  SCM: Git, GitHub'
            }
        }

        stage('📂 Projects') {
            steps {
                echo '🚀  wordpress-devops: 3-tier WordPress deployment using Docker & Ansible with Jenkins CI/CD'
            }
        }

        stage('📜 Certifications') {
            steps {
                echo '✅ AWS Cloud Practitioner - GeeksforGeeks'
                echo '✅ Docker Essentials - Coursera'
                echo '✅ Jenkins Fundamentals - Self-Learning'
            }
        }

        stage('💬 Ask Me About') {
            steps {
                echo 'Docker, Jenkins, Ansible, AWS, Linux, Git, CI/CD, GitOps'
            }
        }

        stage('🌱 Interests') {
            steps {
                echo '⚡ Infrastructure Automation'
                echo '🔁 Building CI/CD Pipelines (Pipeline as Code)'
                echo '✍️  Writing Tech Blogs & Sharing Knowledge'
            }
        }

        stage('📞 Connect With Me') {
            steps {
                echo '🔗 LinkedIn: https://linkedin.com/in/lalit-devops'
                echo '💻 GitHub: https://github.com/lalit192977'
            }
        }
    }

    post {
        always {
            echo '📌 Status: Always Learning | Always Automating | DevOps Forever ❤️'
        }
    }
}


```



<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/></a>   <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/></a>      <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>        <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/></a>            <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>           <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>          <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/></a>         <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/></a>           <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>          <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>               <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/></a>              <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>          <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>



----------------


