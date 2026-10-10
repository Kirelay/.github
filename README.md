# Kirelay 组织公开仓库

维护 Kirelay 的公开组织主页与默认协作文件。目标远程为 `Kirelay/.github`，发布时必须选择 **Public**。本地初始化不代表远程仓库已经创建。

- [公开组织主页](profile/README.md)：对外英文介绍。
- [贡献说明](CONTRIBUTING.md)：跨仓库通用协作要求。
- [Issue 表单](.github/ISSUE_TEMPLATE/bug_report.yml)与 [PR 模板](.github/PULL_REQUEST_TEMPLATE.md)。
- [品牌资产来源](assets/README.md)：原始 Logo 与校验值。

## 维护原则

公开品牌内容及外部协作模板使用英文，维护说明使用中文，文件名和提交信息使用英文。保留各产品仓库自己的构建命令、验收状态和专属约束；这里不复制详细进度。

`profile/README.md` 才是组织主页，根 README 是本仓库说明。受支持的默认协作文件仅在目标仓库缺少自身配置时生效；不会复制进目标仓库的 Git 历史。已有有效 Issue 模板或配置会覆盖整个组织默认 Issue 模板集合。许可证、AGENTS.md 和 CI 不通过此机制自动继承。

目前不设置模板标签、负责人或项目，避免引用各仓库尚未创建的配置。安全报告、支持渠道与行为准则待真实接收渠道确定后再添加。不要将邮件模板中的账户名称视为可用邮箱，不添加虚构的版本徽章、下载入口或开放源代码承诺。

## 发布前检查

1. 核实组织名称、远程仓库是否存在及访问权限。
2. 核实公开主页中的网站和未来增加的仓库链接。
3. 核对 Logo 来源、英文文案与 GitHub 浅色/深色显示。
4. 推送默认分支后检查组织主页，并在缺少自身模板的仓库确认 Issue/PR 模板行为。

官方依据：[组织主页](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)、[默认协作文件](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)。
