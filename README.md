Conference
==========

A conference example to explain how to use enode to develop ddd+cqrs+event souricng application.

����Ŀ��չʾ���ʹ��ENode��������DDD,CQRS,ES�ܹ���Ӧ�ó���

����Ϊ����Bounded Context��
1.ConferenceManagement���������λ�ú�̨����
2.Registration���������û��µ�
3.Payments��������֧��

���в��裺
1.�½�һ����Conference�����ݿ⣬ִ��CreateConferenceTables SQL�ű������������ݿ��е���ر�
2.�½�һ����Conference_EQueue�����ݿ⣬ִ��CreateEQueueTables SQL�ű������������ݿ��е���ر�
3.�½�һ����Conference_ENode�����ݿ⣬ִ��CreateENodeTables SQL�ű������������ݿ��е���ر�
4.HostsĿ¼�µĹ��̶��Ƕ����������̡���������Ҫ�޸�ÿ������������App.config��Web.config�����õ����ݿ������ַ�������Ҫ��ȷ�����ݿ���������ȷ�ģ�
5.����������е��������̣�����˳���������˳��
1��Conference.MessageBroker
2��ConferenceManagement.ProcessorHost
3��Payments.ProcessorHost
4��Registration.ProcessorHost
5��ConferenceManagement.Web
6��Registration.Web

�����Ӧ����������Ŀ�ˡ�
