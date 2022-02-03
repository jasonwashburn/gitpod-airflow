# Super Easy Airflow Sandbox

A super simple way to experiment with, or try out Airflow. 
1. Create a free account at [gitpod.io](http://www.gitpod.io)
2. Launch this repo by clicking on this link  https://gitpod.io/#https://github.com/jasonwashburn/gitpod-airflow.
3. After a small delay, a browser based version of VScode will open and begin building the airflow environment.
4. Shortly thereafter, two more browser windows will open, forwarded to ports 5555 and 8080 on the gitpod (flower and Airflow respectively). Initially they will say they cant connect, but after the services finish launching they will reload automatically.  
    ```
    Username: airflow
    Password: airflow
    ```
5. If you mess something up and want to start over, close the windows and do it again. You'll start with a fresh environment every time.
6. When you're done, just close the windows.
7. If you want to be able to save your DAGS and work on them again later, fork this repo then launch your fork in gitpod by adding https://gitpod.io/# to front of your repo's URL (similar to the link above). Then just commit and push like you normally would. No need to clone the repo locally at all.