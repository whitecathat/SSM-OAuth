* 使用SSM + OLTU框架实现 OAuth Server 授权认证
* 可利用 本地cookie 实现多系统的单点登录 
* 本 demo 只写到，Code2Token这一步，关于后续使用token换取数据，未完成，只写以下简单思路：
> cache 中校验 access_token 是否有效，无效则返回错误信息；有效则返回用户请求的相关数据

* 此 demo 未考虑申请不同权限的操作，只涉及简单的 code以及token下发
