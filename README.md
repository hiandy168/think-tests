# think-tests
QQȺ��647344518   [������Ⱥ](http://shang.qq.com/wpa/qunwpa?idkey=83a58116f995c9f83af6dc2b4ea372e38397349c8f1973d8c9827e4ae4d9f50e)   
�����ַ�� [http://www.must.pw/tests/](http://www.must.pw/tests/) 

### 1. ���    
��ʵ�ʿ����У��ڿ����׶Σ���ʵ��������ȫ���ԣ�������ǵ��ԣ������phpunit���в�����������ʵ�кܶ಻���㣬��Ȼ����Ŀ�������Ҳ������д������������֤����Ŀ����Ժͼ�����ĸ����ʣ�������������   
Ϊ�˼򻯿����е��ԺͲ��ԣ������˴�ģ�飬��ǰ��˿��������ʱ���ʡ����ʱ��Ͳ��衣

![image](https://raw.githubusercontent.com/shulinqian/think-tests/master/common/static/1.jpg)
![image](https://raw.githubusercontent.com/shulinqian/think-tests/master/common/static/2.jpg)
#### Ӧ�ó�����
�ڿ�����ģ�ͻ��߼������ʱ�򣬿��Խ���һЩ����   
������api��sdk����   
����ʱһЩ���Դ��룬����Ҫ�õ���Ŀģ�͵��ļ��Ĳ���   
�ȵ�...


### 2. ��װ
������Ŀ applicationĿ¼
```
git clone git clone https://github.com/shulinqian/think-tests.git tests
```
### 3. ���ʵ�ַ
http://��ĵ�ַ/tests/

### 4. ����
����tests/casesĿ¼���½��ļ�����������  *Test.php, ���� UserTest.php   
run: ÿ�������ļ�����ڣ����涨��Ҫ���Եķ���   
trace: ��Ҫ���Ե���Ϣ����Ҫ��app_debug�� app_trace   
success: ����ͨ��   
error: ���Դ���   
setState: ״̬���棬���ڱ������ݣ������¸����ԣ����磺�����󱣴�id���û������޸Ĳ��ԣ�����ɾ��

### 5.�߼�
1) ���龡����run�����һ�����Է����������� repaire�������������������޸��������Ե����ݻ�ԭ   
2) ������ϸҳ��$testList��key ���ó�1,2,4,8....,   
    ������Ϊ:    
    00000001   
    00000010   
    00000100   
    00001000   
    ...
                
    Ȼ���ڵ�ַ������&mask= ����ݶ�������������в���
    ���磺 /tests/?case=UserTest&mask=3  ��ִ��keyΪ 1��2�ġ�3�Ķ�����00000011    

