# 项目名称
SM2 implementation
# 项目简介

# 完成人
何静 
# 项目流程
##基础参数配置
参考《SM2椭圆曲线公钥密码算法》进行参数配置
![image](https://user-images.githubusercontent.com/104714591/181164678-1dd98da2-da78-4afb-bd58-3099c06637c7.png)
##密钥对生成
![image](https://user-images.githubusercontent.com/104714591/181164747-71cb8429-c1ac-43f3-985a-04aa1221df7f.png)
![image](https://user-images.githubusercontent.com/104714591/181164774-24484ba1-6566-45a0-b7e9-2a0205d3b6ea.png)
##签名部分
###预处理1(获得z值）
![image](https://user-images.githubusercontent.com/104714591/181164865-cb394e99-9997-46af-8266-57b610eb3d0c.png)
###预处理2（获得hash值）
![image](https://user-images.githubusercontent.com/104714591/181164925-621d9f61-3805-4298-8cf3-40f706e5b9a9.png)
###生成签名
![image](https://user-images.githubusercontent.com/104714591/181164984-74005aa5-aae5-4e58-81af-e7520d75755c.png)
###验证签名
![image](https://user-images.githubusercontent.com/104714591/181165031-024c6672-8494-4349-8346-f38456d54ed6.png)
##加密部分
![image](https://user-images.githubusercontent.com/104714591/181165198-5396393b-a946-44c0-a13f-07571ed71c31.png)
##解密部分
![image](https://user-images.githubusercontent.com/104714591/181165238-a6f298d9-f269-4d24-ae6f-d131ae167859.png)
# 代码说明
详见代码，注释十分详尽
# 运行过程截图
![image](https://user-images.githubusercontent.com/104714591/181165383-4788e6a0-ab23-4e3d-b7de-6d6801618b2e.png)
签名验证为true，加密之后的密文进行解密之后与代码中自设的明文对比相同，加解密成功
# 引用参考
[1]http://www.gmbz.org.cn/main/viewfile/20180108023602687857.html
[2]https://blog.csdn.net/u013137970/article/details/84573200?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-1-84573200-blog-120835704.pc_relevant_vip_default&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-1-84573200-blog-120835704.pc_relevant_vip_default&utm_relevant_index=1
[3]https://blog.csdn.net/weixin_43733961/article/details/100148042?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522165882807516782350839667%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=165882807516782350839667&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~hot_rank-21-100148042-null-null.142^v34^pc_search_result_control_group,185^v2^control&utm_term=python%E5%9F%BA%E4%BA%8Egmssl%E5%AE%9E%E7%8E%B0sm2&spm=1018.2226.3001.4187
