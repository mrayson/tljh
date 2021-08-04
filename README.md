# tljh
The littlest jupyter hub extra packages

See [https://tljh.jupyter.org/en/latest/topic/customizing-installer.html#topic-customizing-installer](https://tljh.jupyter.org/en/latest/topic/customizing-installer.html#topic-customizing-installer)

Installation from a cloud machine:
```
curl https://raw.githubusercontent.com/jupyterhub/the-littlest-jupyterhub/master/bootstrap/bootstrap.py \
  | sudo -E python3 -\
  --admin  ubuntu\
  --user-requirements-txt-url https://raw.githubusercontent.com/mrayson/tljh/main/requirements.txt
```
