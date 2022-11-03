# fofa_cnvd
通过公司名称，在fofa上搜索可能存在通用产品的公司；如果想挖掘cnvd证书，可在AI企查等平台上导出注册资金大于5000w的公司到这个脚本中进行通用系统收集。
参考了https://github.com/colind0pe/new_cnvd_fofa_gather和https://github.com/RaiderZP/cnvd_fofa_gather做了自己想要的一些小优化，增加了爬取进度显示和fafo中标题列表全部显示，修改请求fofa时间随机
# 填入fofa账号的email和API_KEY
email = 'YOUR_EMAIL'
api_key = 'API_KEY'
将公司名称放入gs.txt文件中，执行该脚本即可。
python3 cnvd_fofa.py
