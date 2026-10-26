# PR 分工

| 负责人 | PR 范围 | 目录 |
| --- | --- | --- |
| yangbo | 项目基础说明和第一集《夜验》 | `README.md`、`CONTRIBUTING.md`、`episodes/01/` |
| qiaosikao | 第二集《分签》的 10 场连续分镜与本集制作资料 | `episodes/02/` |
| zhangminghan | 第三集《余局》的分镜与本集制作资料 | `episodes/03/` |

## 文件归属

### yangbo PR（当前本地分支：`codex/yangbo-episode1`）

- `README.md`
- `CONTRIBUTING.md`
- `.gitignore`
- `episodes/01/platform-storyboards.md`
- `episodes/01/aicanvas-storyboards.md`
- `episodes/01/period-storyboards.md`
- `episodes/01/art-direction.json`
- `episodes/01/scene-01-period-revision.md`
- `episodes/01/first-cut-script.txt`

### qiaosikao PR（尚未创建）

- `episodes/02/` 下的第二集《分签》文件
- 第二集当前使用 `2-01` 至 `2-10` 的 10 场连续分镜；每场不超过 30 秒

### zhangminghan PR（尚未创建）

- `episodes/03/` 下的第三集《余局》文件
- 第三集的场景、人物连续性和 30 秒内分镜文件

第二、三集的 PR 不应修改 `episodes/01/`，第一集的 PR 也不应代为加入 `episodes/02/` 或 `episodes/03/`。

各负责人从最新 `main` 建自己的分支，只提交自己负责的目录。跨集的情节、道具或时间连续性变更，在 PR 描述里写明影响，供其他两集核对。不要把本地 API Key、AICanvas 任务状态文件或未经导出的云端媒体加入提交。

本地资料包中保留了第二集 15 场历史稿；第二集当前采用 10 场版本。第三集的 30 秒内拆分稿沿用平台导出时的“第1集”场号，正式导入前需要与第三集的场景标题核对。
