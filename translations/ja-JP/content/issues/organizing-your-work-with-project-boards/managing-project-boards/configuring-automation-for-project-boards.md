---
title: '{% data variables.product.prodname_projects_v1 %}の自動化の設定'
intro: '指定されたイベントが発生したときに、IssueやPull Requestを{% data variables.projects.projects_v1_board %}の列に移動させる自動化ワークフローをセットアップできます。'
redirect_from:
  - /github/managing-your-work-on-github/managing-project-boards/configuring-automation-for-project-boards
  - /articles/configuring-automation-for-project-boards
  - /github/managing-your-work-on-github/configuring-automation-for-project-boards
versions:
  feature: projects-v1
topics:
  - Pull requests
  - Projects
  - Issues
  - Project management
shortTitle: 自動化の設定
type: how_to
allowTitleToDifferFromFilename: true
---

{% data reusables.projects.project_boards_old %}

{% data reusables.project-management.automate-project-board-permissions %} 詳しい情報については「[{% data variables.product.prodname_projects_v1 %}の自動化について](/articles/about-automation-for-project-boards)」を参照してください。

{% data reusables.project-management.use-automated-template %}

{% data reusables.project-management.resync-automation %}

{% tip %}

**参考**: すでに自動化を設定している列を編集するには、列の下にある [**Manage**] ボタンをクリックします。

{% endtip %}

1. 自動化したい{% data variables.projects.projects_v1_board %}にアクセスしてください。
2. 自動化したい列で、{% octicon "kebab-horizontal" aria-label="The horizontal kebab icon" %}をクリックします。 ![編集アイコン](/assets/images/help/projects/edit-column-button.png)
3. [**Manage automation**] をクリックします。 ![[Manage automation] ボタン](/assets/images/help/projects/manage-automation-button.png)
4. [Preset] ドロップダウンメニューで、自動化のプリセットを 1 つ選びます。 ![メニューから自動化のプリセットを選択](/assets/images/help/projects/select-automation.png)
5. 列に設定したいワークフロー自動化を選択します。 ![列の自動化オプションのリスト](/assets/images/help/projects/select-automation-options-existing-column.png)
6. [**Update automation**] をクリックします。

## 参考リンク
- 「[{% data variables.product.prodname_projects_v1 %}の自動化について](/articles/about-automation-for-project-boards)」
