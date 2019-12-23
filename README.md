
# Bài 1: So sánh gi?a git commit -m "Message" và git commit -am "Message"
- git commit -m "Message": d? d?y thông tin lên Local Respository
- git commit -am "Message" : ghi dè l?i message c?a commit tru?c dó
# Bài 2: Repository là gì

Repository hay còn g?i là Repo, d?ch ra ti?ng Vi?t có nghia là kho, 
dây chính là noi ch?a t?t c? mã ngu?n cho m?t d? án du?c qu?n lý b?i Git
# Bài 3: Các bu?c d? push code lên repository server.	
 * T?o 1 repo trên máy 	     : git init
 * T?o nhánh riêng: git branch <tên nhánh>
 * Chuy?n sang branch v?a t?o d? code: git checkout <tên nhánh>
    G?p c? 2 bu?c trên: git checkout -b <tên nhánh>
 * Ch?n file       	     : git add <tên file>
     N?u ch?n t?t c? 	     	 : git add.
 * Commit lên local	     : git commit -m "message"
 * Ð?y code lên Repo server: git push origin <tên nhánh>
# Bài 4: So sánh git merge và git rebase
- git merge: g?p nhánh vào g?c master
Sau m?t th?i gian c?p nh?t các file và push lên git trên branch m?i,
 bây gi? mình c?n ghép (merge) code l?i vào nhánh g?c (master). 
Tru?c tiên, c?n ph?i checkout ra kh?i branch hi?n t?i c?n g?p d? vào
 branch master, sau dó thì dùng l?nh merge d? ghép branch m?i vào master:
git checkout master
git merge <new_branch>
- git rebase: g?p nhi?u commit làm 1 commit
git rebase -i HEAD~<s? commit mu?n g?p>
git rebase <Nhánh chính>
git rebase <Nhánh mu?n g?p vào nhánh chính>
# Bài 5: Pull Request là gì ? Cách t?o Pull Request
- Pull request du?c t?o ra d? dua nh?ng file source code c?a b?n lên 1 host
 chung noi m?i ngu?i có quy?n truy c?p s? truy c?p vào và cùng review, 
d? l?i comment trên nh?ng file source code dó. Lúc này th?i gian review 
và d?a di?m review source code không còn là v?n d? - dó cung chính là 
m?c dích t?o ra pull request!
__Cách t?o Pull Request__
+ T?o branch riêng c?a mình d? push code mình lên
+ Di chuy?n sang branch chính d? review
# Bài 6: M?t s? cú pháp markdown
+ Tiêu d?: ch? nh? d?n
# h1
## h2
### h3
+ Nh?n m?nh, Highlight
*word* : in nghiêng
**word**: bôi d?m
***word***: v?a in nghiêng, v?a bôi d?m
+ Link, Image:
**Link**: [Title](link)
VD: [Markdown](http://https://vi.wikipedia.org/wiki/Markdown)
**Image**: ![alt](link)
VD: ![alt](http://http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png)
+ List
List d?ng g?ch d?u dòng
* Item
VD: 
	* item 1
    * item 2
    * 
List d?ng s?
1. item
2. item

# Bài 7: Cách vi?t daily report b?ng Markdown
