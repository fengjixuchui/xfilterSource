		�Ѷ����˷���ǽ 2.1 Դ����
	       ��Ȩ���� (C) �Ѷ���ȫʵ����
		http://www.filseclab.com
                  filsoft@filseclab.com
		   2002 �� 12 �� 22 ��
===============================================================

��ʹ�÷Ѷ����˷���ǽԴ����֮ǰ���������Ķ��û�����Э��(��Ŀ¼
�� Agreement.txt �ļ�)��

�Ѷ����˷���ǽ 2.1 Դ������� XFILTER.EXE, XFILTER.DLL, 
XPACKET.VXD ( ����95/98/ME�� ) , XAPCKET.SYS ( ���� 2000/XP �� )
��Դ����

�˴������û�а��������ĳ���Ҫ�����Щ�������ͨ�����ذ�װ
���õ�����װ������ѵģ�ʹ�� ZIP ���ݵ�ѹ����ʽ���� ZIP ���߽�
ѹ��


��Ҫ�ļ�/Ŀ¼˵��

Xfilter.dsw 	- VC �������ļ����������¹���
		- TcpIpDog\TcpIpDog.dsp
		- xfilter\xfilter.dsp
		- xpacket2k.dsp ( ���� 2000/XP �� )
		- xpacket9x.dsp ( ���� 95/98/ME �� )

Common 	  - ��Ź��ô����ļ�
RELEASE   - ��ű����ĳ���
TcpIpDog  - XFILTER.DLL �Ĵ���
XFILTER   - XFILTER.EXE �Ĵ���
xpacket2k - XPACKET.SYS �Ĵ��� (2000/XP ��Ż��д�Ŀ¼)
xpacket9x - XPACKET.VXD �Ĵ��� (95/98/ME ��Ż��д�Ŀ¼)


��̹���

Microsoft Visual C++ 6.0
DDK For Windows 2000 (�� 2000/XP ����Ҫ)
VToolsD For Windows 98 (�� 95/98/ME ����Ҫ)


XFILTER.EXE ����˵�� (��Windows 98/2000 �¾���)

�� VC �򿪹������ļ� XFilter.dsw��ѡ��ǰ����Ϊ "XFilter"����
"Build" ��ť�������� XFILTER.EXE ���� Release Ŀ¼��


XFILTER.DLL ����˵�� (��Windows 98/2000 �¾���)

�� VC �򿪹������ļ� XFilter.dsw��ѡ��ǰ����Ϊ "TcpIpDog"����
"Build" ��ť�������� XFILTER.DLL ���� Release Ŀ¼��


XPACKET.SYS ����˵�� (������ 2000/XP ��) (ֻ���� Windows 2000 ��)

���ȱ�֤��װ�� DDK For Windows 2000��

�� VC �򿪹������ļ� XFilter.dsw������ʹ�� XPacket2k\Build.bat
��ɣ�������Ҫ���ݲ�����������Ҫ�������ù������е� "Xpacket2k"
���̵������б�����������÷���Ϊ: VC ������ -> Project �˵� -> 
Settings �˵� -> �ڵ����Ի�����ѡ�� Xpacket2k ���� -> Settings For
ѡ�� Debug �� Release -> General -> Build Command Line Ϊ

build.bat %DDKROOT% free F: F:\xfilter2\xpacket2k %SystemRoot%

��һ������ %DDKROOT% ��ʾ DDK ��װĿ¼�Ļ������������Բ��ø��ġ�
�ڶ������� free ��ʾ����Ϊ release �汾��checked ��ʾ����Ϊ debug 
	   �汾��
���������� F: Դ���������̷�����Ҫ�޸�Ϊ�Լ�����ȷ�̷���
���ĸ����� F:\xfilter2\xpacket2k Դ�������ڵ�·������Ҫ�޸�Ϊ�Լ�
	   ����ȷ·����
��������� %SystemRoot% ��ʾϵͳĿ¼�Ļ����������������Ὣ������ 
	   Xpacket.sys �Զ����Ƶ�ϵͳĿ¼��һ��ΪWinnt\system32��

�޸ĺ�ȷ�ϣ�Ȼ��ѡ��ǰ����Ϊ "XPACKET2K"���� "Build" ��ť������
��� XPACKET.SYS �Զ����Ƶ� Release Ŀ¼��ϵͳĿ¼��


xpacket.sys For XP �ı���˵����

2.0.5�����˶�XP��֧�֣����� Win 2000 �� Win XP ����������������ݣ�����û�����±�д�������򣬵���Ϊ����߼����ԣ����ʹ��DDK For XP��xpacket2k�������±��룬���뷽�����£�

1. ��װXP����ϵͳ
2. ��װDDK For XP
3. ��"Start"->"All Program"->"Development Kits"->"Windows DDK 2600"->"Build Environments"->"Win XP Free Build Environment"������Release�汾������"Win XP Checked Build Environment"������Debug�汾��
4. ���������к��л���Դ�������ڵ�xpacket2kĿ¼
5. ִ�����Build.exe -cZ��
6. ��ɱ��롣


XPACKET.VXD ����˵�� (������ 95/98/ME ��) 

�� Windows 98/2000 �¾��ɱ��룬�����뱣֤ 98/2000 ͬʱ��װ��ͬһ̨
����������ұ��뱣֤�� Windows 98 �°�װ�� VToolsD For Windows 98��

�� VC �򿪹������ļ� XFilter.dsw��Ȼ��ѡ��ǰ����Ϊ "XPACKET9X"��
�� "Build" ��ť�������� XPACKET.VXD �Զ����Ƶ� Release Ŀ¼��
���Ը�������༭ Xpacket9x\Build.bat��Debug �� Release �汾����
��Ҫ�༭ Xpacket9x\xpacket.mak �ļ����� xpacket.mak ��

DEBUG = 1 ʱ��ʾΪ Debug �汾
#DEBUG = 1 ע�͵�DEBUG�������Ϊ Release �汾


===============================================================
�ڱ�������п��ܳ��־�����󣬵��ⲻӰ�������������У������
���������ܽ���Ĵ�������������ϵ��



��װ

Ҫ�����б���õĳ����谴��һ�²�����а�װ��

1. Win95/98/ME ���轫 Xpacket.vxd ���Ƶ� Windows\System Ŀ¼, 
   ���� Release\Xpacket9x.reg ����ע�����
   Windows2000 ���轫 Xpacket.sys ���Ƶ� Winnt\System32 Ŀ¼��
   ���� Release\Xpacket2k.reg ����ע�����

2. ��������ģʽִ�� xfilter.exe -install��

3. ������������ɰ�װ��


ж��

1. ��������ģʽִ�� xfilter.exe -remove��

2. Win95/98/ME ɾ��ע�����֧ 
   HKEY_LOCAL_MACHINE\System\CurrentControlSet\Services\VxD\XPACKET
   Windows2000 ɾ��ע�����֧ 
   HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\XPacket

3. �������������ж�ء�





