#  记一次FIL节点被盗币的经历

## FIL 节点先被黑客拿到了owner权限，然后再把节点的币分批一点点提走，具体过程如下：
* 在2月份，节点被黑客入侵，修改了对应的owner地址
* 在随后的几天，节点的币被一次次分批拿走

## 教训:
* 节点的安全一定要做好，登录控制用RSA私钥。
* FIL节点的owner 权限和普通的提交权限一定要分开。
* owner 地址的私钥一定不能放在节点上。
* 节点的币要及时提走，降低损失。
* 个人不可信，一定要从制度上保证安全。