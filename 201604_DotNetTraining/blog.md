#### 20160410
recommend book:《.NET Primer》

***

##### use StringBuilder.Append instead of +
string a="a";
string b="b";
string c=a + b; -- this format will create two new instance but need to use the stringBuilderInstead

***

##### Exception Capture Management
- handle the specified exception with in related exception block, don't raise to others exception
- print log within exception handing
- expaction handle would be bigger part than a normal flow

***

##### .Net Assembly
- Managed(Assembly, *.exe (contain Main), *.DLL) & Unmanaged (Dymanic Link Labrary)
- Security control 360 Vs MS -->  system file mapping Vs  GAC solution
- GAG and Deploy Strong Name Assembly


##### Generic 泛型
- <http://www.cnblogs.com/kid-li/archive/2006/11/29/577045.html>

#####Reflect 反射
- <http://blog.csdn.net/educast/article/details/2894892>
- <http://www.cnblogs.com/psunny/archive/2009/08/19/1548529.html>


