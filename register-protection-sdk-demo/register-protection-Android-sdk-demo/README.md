ע�ᱣ�� Android sdk ʾ�� demo
===

### demo ���в���

* 1������ģ��ҵ���ˣ�check demo�����з�����register-protection-check-demoĿ¼

* 2���޸� MainActivity.java �� onCreate���������� bussinessId�����£�
```
     RjsbHandler.setBusinessId(getApplicationContext(), "YOUR_BUSINESS_ID");
```
* 3���޸� RegistTask.java�� PostData�����е�url����
```
     String url = "http://localhost:8183/register.do";
     // ���磬�滻���£�
    String url = "http://10.240.132.43:8183/register.do";
```	
* 4�����ˣ����ú��޸���ɣ��������м���
