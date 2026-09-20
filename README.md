# Colo Sources

由 Colo 在本机网络筛选并经实际 Worker HTTPS 验证的 Cloudflare 国家源（一级 Top）。

- `countries/XX.txt`：每行一个入口 IP 或 IP:端口，XX 为国家/地区代码。
- `index.json`：国家名称、上线状态、入口数量与文件路径。
- 未上线或暂无有效结果的国家文件为空。地区表示实测机房归属，不保证出口地区。
- 自动更新需要 Colo 正在运行且网络可用；结果变化会合并为一次提交，相同结果不重复提交。
- 更新时间见 GitHub 最近提交；结果是发布时快照，具体可用性取决于使用者网络。

使用 GitHub 文件页面的 Raw 地址订阅。仓库不包含 Token、Worker 域名或本机配置。
