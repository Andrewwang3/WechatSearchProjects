�ݹ�ץȡ΢���������
ʹ��Scrapy���� ���� ʹ��requests+BeautifulSoup


ʹ��Scrapy������
	��querystring�滻Ϊ��Ҫ��ѯ�ĵ���
	type����ѡ��
	i��range��Χ���Ե�������Ӧ��ѯ���������ҳ����Ŀ
#############################################################################################
'''΢����������'''
name = "wechat"

start_urls = []
querystring = u"�廪"
type = 2 # 2-���£�1-΢�ź�
for i in range(1, 5, 1):
	start_urls.append("http://weixin.sogou.com/weixin?type=%d&query=%s&page=%d" % (type, querystring, i))
# print start_urls



