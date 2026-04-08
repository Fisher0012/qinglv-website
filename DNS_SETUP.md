# qinglv.app DNS 配置说明

网站已部署在 GitHub Pages：https://fisher0012.github.io/qinglv-website/

## 绑定自定义域名 qinglv.app

在 GoDaddy (godaddy.com) → My Domains → qinglv.app → DNS → 添加以下记录：

### A 记录（4条，全部 TTL=600）
| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

### CNAME 记录（1条）
| Type | Name | Value |
|------|------|-------|
| CNAME | www | fisher0012.github.io |

配置完成后 24-48 小时内生效。
