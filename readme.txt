$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
$ mkdir learngit //�����ļ���
$ cd learngit  //���ļ���
$ pwd //��ʾ��ǰĿ¼
/Users/michael/learngit
git init //�����ֿ�

git add  readme.txt // �� readme.txt�ļ���ӵ��ֿ�

git add -A   // ������иĶ�

git add *     // ����½��ļ����޸ģ����ǲ�����ɾ��

git add .    // ����½��ļ����޸ģ����ǲ�����ɾ��

git add -u   // ����޸ĺ�ɾ�������ǲ������½��ļ�

git reset <file> // �����ύ�����ļ�

git reset        // unstage all due changes

git commit -m '�ύ��Ϣ' //���ļ��ύ���ֿ�  -m �����ύ��˵��

git status   //���յ�ǰ�ֿ�״̬

git diff //�Ƚϲ���

git log//��־ --pretty=oneline

git relog //��¼���ÿһ������

git reset HEAD //���ذ汾��

git checkout 


git push -u origin master //�ύԶ��

�鿴��֧��git branch

������֧��git branch <name>

�л���֧��git checkout <name>

����+�л���֧��git checkout -b <name>

�ϲ�ĳ��֧����ǰ��֧��git merge <name>

ɾ����֧��git branch -d <name>


��git log --graph  --pretty=oneline������Կ�����֧�ϲ�ͼ��

git merge --no-ff -m 'merge with no-ff' dev //ʹ��dev��֧��ƴ,��ֹʹ��fast wforward

