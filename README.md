# Winter-drogon

```sh


if [ ! -d ~/Winter-drogon ]; then cd ~/ && git clone https://github.com/AndyInAi/Winter-drogon.git; fi


# 运行

cd ~/Winter-drogon && chmod +x ./Winter-drogon && ./Winter-drogon

# Starting HTTP server at http://0.0.0.0:8080/


# 测试
curl http://localhost:8080/


# 或者编译源代码后运行


# 安装编译环境

apt install -y git gcc g++ cmake libjsoncpp-dev uuid-dev zlib1g-dev zlib1g-dev


# 编译源代码
cd ~/Winter-drogon/build && cmake .. && make -j $(nproc)


# 运行
cd ~/Winter-drogon && ./build/Winter-drogon


# Starting HTTP server at http://0.0.0.0:8080/


# 测试
curl http://localhost:8080/


```
