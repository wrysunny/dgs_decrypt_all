# dgs_decrypt_all  
解密dgs加密的文件(解密文件和生成卸载码)功能  
# 使用参数  

在命令行中运行  
```text   
Usage of C:\Users\svf\Desktop\run.exe:
  -infile string
        输入可能疑似加密文件，检测文件是否为加密文件
  -outfile string
        输出解密后的文件
  -uninstall string
        需要输入提示码，会返回卸载码
```  

# 演示视频  
## 解密文件  
![]('/demo.gif')
## 生成卸载码  
![]('uninstall.gif')

# 其他说明  
使用upx进行压缩，仅针对本单位加密的文件进行解密.  
其他单位加密的文件可能解密不了，可提issues解决（需提供enterpriseId）  
