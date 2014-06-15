FTP_WEB_Server
==============

a simple super FTP and WEB server and FTP client

服务器端：
FTP工作目录（需要修改，也即FTP上传<下载>的工作目录）：
    （DataStructAndConstant.h）#define DEFAULT_WORKPATH "D:\\CtestCode\\testSrcFTP"

客户端：
FTP工作目录（FTP下载之后文件保存路径）
    #define DST_FTP_DIR "D:\\CtestCode\\testDstFTP"
    
也可以建立目录
	D:\CtestCode\testSrcFTP
	D:\CtestCode\testDstFTP
	并在testSrcFTP中加入一些文件和文件夹（不超过30个）

start server
start client:
    ls (列出当前目录下所有文件)
    pwd (输出当前所在路径)
    cd dir (进入dir文件夹)
    cd .. （返回上一目录）
    get filename （下载文件filename）
