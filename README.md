
# B�i 1: So s�nh gi?a git commit -m "Message" v� git commit -am "Message"
- git commit -m "Message": d? d?y th�ng tin l�n Local Respository
- git commit -am "Message" : ghi d� l?i message c?a commit tru?c d�
# B�i 2: Repository l� g�

Repository hay c�n g?i l� Repo, d?ch ra ti?ng Vi?t c� nghia l� kho, 
d�y ch�nh l� noi ch?a t?t c? m� ngu?n cho m?t d? �n du?c qu?n l� b?i Git
# B�i 3: C�c bu?c d? push code l�n repository server.	
 * T?o 1 repo tr�n m�y 	     : git init
 * T?o nh�nh ri�ng: git branch <t�n nh�nh>
 * Chuy?n sang branch v?a t?o d? code: git checkout <t�n nh�nh>
    G?p c? 2 bu?c tr�n: git checkout -b <t�n nh�nh>
 * Ch?n file       	     : git add <t�n file>
     N?u ch?n t?t c? 	     	 : git add.
 * Commit l�n local	     : git commit -m "message"
 * �?y code l�n Repo server: git push origin <t�n nh�nh>
# B�i 4: So s�nh git merge v� git rebase
- git merge: g?p nh�nh v�o g?c master
Sau m?t th?i gian c?p nh?t c�c file v� push l�n git tr�n branch m?i,
 b�y gi? m�nh c?n gh�p (merge) code l?i v�o nh�nh g?c (master). 
Tru?c ti�n, c?n ph?i checkout ra kh?i branch hi?n t?i c?n g?p d? v�o
 branch master, sau d� th� d�ng l?nh merge d? gh�p branch m?i v�o master:
git checkout master
git merge <new_branch>
- git rebase: g?p nhi?u commit l�m 1 commit
git rebase -i HEAD~<s? commit mu?n g?p>
git rebase <Nh�nh ch�nh>
git rebase <Nh�nh mu?n g?p v�o nh�nh ch�nh>
# B�i 5: Pull Request l� g� ? C�ch t?o Pull Request
- Pull request du?c t?o ra d? dua nh?ng file source code c?a b?n l�n 1 host
 chung noi m?i ngu?i c� quy?n truy c?p s? truy c?p v�o v� c�ng review, 
d? l?i comment tr�n nh?ng file source code d�. L�c n�y th?i gian review 
v� d?a di?m review source code kh�ng c�n l� v?n d? - d� cung ch�nh l� 
m?c d�ch t?o ra pull request!
__C�ch t?o Pull Request__
+ T?o branch ri�ng c?a m�nh d? push code m�nh l�n
+ Di chuy?n sang branch ch�nh d? review
# B�i 6: M?t s? c� ph�p markdown
+ Ti�u d?: ch? nh? d?n
# h1
## h2
### h3
+ Nh?n m?nh, Highlight
*word* : in nghi�ng
**word**: b�i d?m
***word***: v?a in nghi�ng, v?a b�i d?m
+ Link, Image:
**Link**: [Title](link)
VD: [Markdown](http://https://vi.wikipedia.org/wiki/Markdown)
**Image**: ![alt](link)
VD: ![alt](http://http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png)
+ List
List d?ng g?ch d?u d�ng
* Item
VD: 
	* item 1
    * item 2
    * 
List d?ng s?
1. item
2. item

# B�i 7: C�ch vi?t daily report b?ng Markdown
