usage: officeweb365.py [-h] [-a TARGET] [-l URLFILE] [-i HOSTFILE] [-p PORT] [-o OUTPUT] [-t THREAD]

options:
  -h, --help            show this help message and exit
  -a TARGET, --target TARGET
                        检测单个url
  -l URLFILE, --urlfile URLFILE
                        批量检测,url的txt,每行一个
  -i HOSTFILE, --hostfile HOSTFILE
                        批量检测,ip的txt,每行一个,使用http请求
  -p PORT, --port PORT  设置端口,逗号或短横杠分割,默认8088
  -o OUTPUT, --output OUTPUT
                        输出文档
  -t THREAD, --thread THREAD
                        线程，默认4
