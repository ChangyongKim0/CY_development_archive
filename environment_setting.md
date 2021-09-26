# Install Python

1. python 설치

1. 기존 python 2.x 삭제

    ```bash
    sudo apt purge -y python2.7-minimal
    ```

1. python 3.x 의 python 링크 폴더 생성

    ```bash
    sudo ln -s /usr/bin/python3.7 /usr/bin/python
    ```

```bash
# Remove python2
sudo apt purge -y python2.7-minimal

# You already have Python3 but 
# don't care about the version 
sudo ln -s /usr/bin/python3 /usr/bin/python

# Same for pip
sudo apt install -y python3-pip
sudo ln -s /usr/bin/pip3 /usr/bin/pip

# Confirm the new version of Python: 3
python --version
```