# xianyang.github.io

学术主页（纯静态 HTML），对应仓库 `xianyang998/xianyang.github.io`，上线地址：`https://xianyang998.github.io`

## 当前状态

框架已生成，内容为占位符，等待填入真实信息：

| 占位符 | 需替换为 |
|---|---|
| `Your Name` | 姓名（英文） |
| `Your Position` | 职位 |
| `Your Affiliation` | 单位 |
| `City, Country` | 城市 |
| `Research Area 1/2/3` | 研究方向 |
| `youremail@example.com` | 邮箱 |
| `Paper Title` / `Journal Name, Year` | 论文信息 |

## 部署（首次）

仓库已存在且为空，任选一种方式上传：

**方式 A：网页上传**
1. 打开 https://github.com/xianyang998/xianyang.github.io
2. Add file → Upload files → 上传 `index.html` → Commit
3. Settings → Pages → Source 选 `Deploy from a branch`，Branch `main` / `(root)` → Save

**方式 B：命令行（需先用 xianyang998 账号认证）**
```bash
cd xianyang.github.io
git init
git add .
git commit -m "init homepage"
git remote add origin https://github.com/xianyang998/xianyang.github.io.git
git push -u origin main
```

**方式 C：GitHub Desktop**
File → Add local repository → 选此文件夹 → Publish repository（先登录 xianyang998 账号）

## 后续修改

改 `index.html` 后重新提交推送即可，1 分钟内生效。
