# details on https://docs.nickuc.com/

Commands 
/nlogin <command> [arguments]: the central command of the plugin. It is generally used for administration.
/nlogin <command> [参数] ：插件的中心命令。一般用于行政管理。
/nlogin support: lists support contacts.
/nlogin support ：列出支持联系人。
/nlogin version: shows plugin version information.
/nlogin version ：显示插件版本信息。
/nlogin changepass <player> <new password>: changes a player's password.
/nlogin changepass <player> <新密码> ：更改玩家的密码。
/nlogin delete <player>: deletes a player's account
/nlogin delete <player> ：删除玩家帐户
🚨 UUID data may be lost after performing this operation. Don't be confused with the /nlogin unregister command.
🚨 执行此操作后，UUID 数据可能会丢失。不要与/nlogin 取消注册命令混淆。
/nlogin dupeip <player/ip>: lists accounts with the same IP address.
/nlogin dupeip <player/ip> ：列出具有相同 IP 地址的帐户。
/nlogin forcelogin <player>: forces the login of an account.
/nlogin forcelogin <player> ：强制帐户登录。
/nlogin unregister <player>: removes an account's password.
/nlogin unregister <player> ：删除帐户的密码。
/nlogin verify <player>: lists an account's information.
/nlogin verify <player> ：列出帐户的信息。
/nlogin reload: reloads the plugin settings.
/nlogin reload ：重新加载插件设置。
/nlogin update: controls the update settings.
/nlogin update ：控制更新设置。
/nlogin spawn <action> <type>: controls the teleportation mechanism.
/nlogin Spawn <action> <type> ：控制传送机制。
/changepassword <current password> <new password>: changes the registered password.
/changepassword <当前密码> <新密码> ：更改注册密码。
/discord [arguments] 💎: used to configure a Discord account as a second factor.
/discord [arguments] 💎：用于将 Discord 帐户配置为第二个因素。
/email [arguments] 💎: used to configure an email as a second factor.
/email [arguments] 💎：用于将电子邮件配置为第二个因素。
/login <password>: authenticates the registered player.
/login <password> ：验证注册玩家的身份。
/offline 💎: marks the account as offline.
/offline 💎：将帐户标记为离线。
/premium 💎: marks the account as premium.
/premium 💎：将帐户标记为高级。
If executed via the console, enables/disables an account's premium mode.
如果通过控制台执行，则启用/禁用帐户的高级模式。
/register: registers a password.
/register ：注册密码。
/unregister: unregisters your account.
/unregister ：取消注册您的帐户。
This command is disabled by default. To activate it, go to the plugin's config.yml.
默认情况下禁用此命令。要激活它，请转到插件的config.yml 。
* 💎 = Premium version exclusive command.
* 💎 =高级版专属命令。

Permissions 
nlogin.admin: differentiates a player from an administrator.
nlogin.admin ：区分玩家和管理员。
It grants access to special notifications and administrative commands.
它授予对特殊通知和管理命令的访问权限。
Bypass and 2FA:
绕过和 2FA 
nlogin.bypass.discord: skips registering a Discord account if the option to require Discord linking is enabled.
nlogin.bypass.discord ：如果启用了需要 Discord 链接的选项，则跳过注册 Discord 帐户。
nlogin.bypass.email: skips registering an email if the option to require linking an e-mail is enabled.
nlogin.bypass.email ：如果启用了要求链接电子邮件的选项，则跳过注册电子邮件。
nlogin.force.discord: force Discord 2FA authentication even if IP is not changed.
nlogin.force.discord ：即使 IP 未更改，也强制进行 Discord 2FA 身份验证。
nlogin.force.email: force email 2FA authentication even if IP is not changed.
nlogin.force.email ：即使 IP 未更改，也强制进行电子邮件 2FA 身份验证。
Commands: 命令
nlogin.command.nlogin.changepass: gives access to the /nlogin changepass command.
nlogin.command.nlogin.changepass ：提供对/nlogin changepass命令的访问。
nlogin.command.nlogin.changeuuid: gives access to the /nlogin changeuuid command.
nlogin.command.nlogin.changeuuid ：允许访问/nlogin changeuuid命令。
nlogin.command.nlogin.delete: gives access to the /nlogin delete command.
nlogin.command.nlogin.delete ：允许访问/nlogin delete命令。
nlogin.command.nlogin.register: gives access to the /nlogin register command.
nlogin.command.nlogin.register ：提供对/nlogin register命令的访问。
nlogin.command.nlogin.unban: gives access to the /nlogin unban command.
nlogin.command.nlogin.unban ：允许访问/nlogin unban命令。
nlogin.command.nlogin.unregister: gives access to the /nlogin unregister command.
nlogin.command.nlogin.unregister ：提供对/nlogin unregister命令的访问。
nlogin.command.nlogin.verify: gives access to the /nlogin verify command.
nlogin.command.nlogin.verify ：允许访问/nlogin verify命令。
nlogin.command.discord: gives access to 2FA via Discord /discord.
nlogin.command.discord ：通过 Discord /discord提供对 2FA 的访问。
nlogin.command.email: gives access to 2FA via email /discord.
nlogin.command.email ：通过电子邮件/discord提供对 2FA 的访问。