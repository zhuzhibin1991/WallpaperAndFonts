��ֽ��
ѡ���ֽ��ȴ�һ��
-------------------
���壺
ǰ���������ֻ���root/��Ӧ��ֻ�޸����������壬��������ǰ���ϵͳ��������Ϊ��������
Ӧ������ʱֻ���������������ʽ��
������Բ
��������
�����п�
��������
��app�����������������ִ������adb ��������ֻ��󼴿ɸ���ϵͳ����
adb root
adb remount
adb pull /data/data/com.wind.wallpaperandfontsapp/files/ ./test
adb push test\fonts.xml system/etc/
adb push test\new.ttf system/fonts/
adb reboot