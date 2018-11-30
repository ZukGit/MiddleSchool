# 数学

## 人民教育出版社教材_八年级

电子书网址： http://www.shuxue9.com/pep/cz8s/ebook/7.html
http://www.shuxue9.com/pep/cz8s/ebook/161.html
http://www.shuxue9.com/pep/cz8s/ebook/167.html



http://www.shuxue9.com/pep/cz8s/ebook/001.jpg
http://www.shuxue9.com/pep/cz8s/ebook/167.jpg

# 英语

## 人民教育出版社教材_八年级
电子书网址:  http://www.wsbedu.com/wu51/keben.asp?wai=886&page=1


#  物理  

## 人民教育出版社教材_八年级
电子书网址:  http://www.wsbedu.com/wu51/keben.asp?wai=977&page=1


#  地理 
## 新球地图出版社_八年级


# 生物学

## 江苏凤凰教育出版社__八年级


#  化学


#  语文


# 道德政治





#  中国历史 



# 网站


            



| 网站名称 | 网址 | 备注 |
| ------ | ------ | ------ |
| 中考网 | http://www.zhongkao.com/    | X |
|  |  |  |




if __name__ == '__main__':
    cookiesStr = """__guid=66859048.1158483362161654500.1518005152651.3875; cdb_cookietime=2592000; cdb_auth=Vwd79Mo3xKHsS5P%2FgwDFjNZ1aJlZhljqDAxg48oRrKfQEGoVnAACJylkGahC8rYSoA; cdb_visitedfid=5D41D61D59D53D85D86D60D57D11D65; is_use_cookiex=yes; cdb_fid5=1520128530; cdb_sid=rzs7cS; cdb_oldtopics=D2131051D1996862D1996861D1996872D2131070D2131071D2131072D; monitor_count=259; is_use_cookied=yes"""


    rootBegin ="http://www.shuxue9.com/pep/cz8s/ebook/001.jpg"
    rootBegin ="http://www.shuxue9.com/pep/cz8s/ebook/107.jpg"

    for i in range(1,108):   # 遍历所有的页面
        if(i < 10):
            rootbase_url = "http://www.shuxue9.com/pep/cz8s/ebook/00" + str(+i + 0) +".jpg"
        if(i < 100):
            rootbase_url = "http://www.shuxue9.com/pep/cz8s/ebook/0" + str(+i + 0) +".jpg"
        if(i >= 100):
            rootbase_url = "http://www.shuxue9.com/pep/cz8s/ebook/" + str(+i + 0) +".jpg"
        mPageArray.add(rootbase_url)

print("mPageArray length:"+ str(mPageArray.__len__()))
