大致把iOS版本 QQ 和 Wechat 在使用的服務器 ip 整理出來了<br/>
从<code>/16</code>可以看出这些IP范围很广，很可能影响其他无辜IP <br/>
并且内容没经过检查，可能有不相关的IP</br>
对[Surge.conf](https://github.com/Qinyongr/tencent_IP/blob/master/Surge.conf)的详细说明如下：<br/>
此处为供Surge使用的配置文档，iOS和mac均可使用</br>
本段内容放在<code>[Rule]</code>下方</br>
本段内容使用了自定义的Proxy Group，配置如下：<pre>
QQ = select, DIRECT, REJECT
Wechat = select, DIRECT, REJECT</pre><br/>
如果不要现有的<code>QQ</code>和<code>Wechat</code>的Proxy Group，</br>
可将所有的<code>QQ</code>和<code>Wechat</code>替换成为需要的Group的名称即可
