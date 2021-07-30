# Day 1: Getting Started with GitHub Flow

### In Class Activities:
- Work in the class repository together, a slide deck of images and captions.
- Talk about [GitHub Flow](https://guides.github.com/introduction/flow/).
- Take a brief tour of what a GitHub repository looks like.
- Comment on an issue.
  - See what an issue is like, disuss what issues are used for.
  - Behind the scenes, we use this comment to add you as a collaborator.
  - We also create a document for you to work on later.
- Clone the repository locally, and [get the site set up to build locally](https://github.com/githubtraining/caption-this#instructions-local-setup).
- Together, practice GitHub flow to change your page of the slide deck and add a caption.
  - Creating a branch.
  - Making (a) commit(s).
- Create a pull request.

### After Class Activities:

#### 1. Complete a code review of someone else's slide file.
  - Since you're partnered, and everyone wants a review, both you and your partner should complete a review of different pull requests.
  - Find an open pull request with no review in the class repository
  - Leave a review of the changes within the pull request (Not sure how? [Click here](https://help.github.com/articles/about-pull-request-reviews/) for more information.)

#### 2. Pick another open issue to work on together. These tasks could be creating more slides, adding a new layout, or adding tests.
  - In the class repository, there are several open issues. You can find them by looking at the Project page or in the Issues tab. Each issue lists a different task you can complete to improve the class repository. 
  - Pick an issue, and follow the instructions linked within it. 
  - Regardless of which issue you choose, you will practice the GitHub flow again on your own and create a new pull request.

----

# [ja] Day 1: Getting Started with GitHub Flow

### クラスでの演習:
- class repository （画像とキャプションがあるスライドを含む）で一緒に作業する
- [GitHub Flow](https://guides.github.com/introduction/flow/)　について説明する
- GitHub リポジトリとはどういうものか、手短に説明する
- "Comment here to be added as a collaborator" というタイトルの issue にコメントしてもらう
  - issue とはどういうものかを説明し、どのような場面で利用できるかを話し合う
  - 背景として、ここでコメントしてもらうのは、次のワークで collaborator として追加するためである
  - We also create a document for you to work on later.
- class repository をローカルにクローンし、[ローカルでセットアップする](https://github.com/githubtraining/caption-this#instructions-local-setup)（※ 今はこのセットアップ手順の記載はない。[以下](#formerly-instructions-local-setup)に同時期のコミットから該当箇所を抜粋）
- 併せて、 GitHub Flow に沿った実演として、スライドのキャプションを更新する
  - ブランチを作成する
  - コミットを作成する
- プルリクエストを作成する

### クラスでの演習ののち:

#### 1. 他の誰かのスライドファイルのコードレビューを完了する

- パートナーを組み、パートナー同士でそれぞれのプルリクエストのレビューを完了する
- class repository で、レビューされていないプルリクエストを見つける
- プルリクエストで変更に対しレビューを残す（不明な場合は [こちら](https://help.github.com/articles/about-pull-request-reviews/) をご参考ください）

#### 2. issue を選択し、一緒に作業する。追加のスライドを作成する、新しいレイアウトを追加する、テストを追加する

- class repository に、いくつかの未解決の issue がある。Project ページまたは Issues タブからそれらを確認し、この class repository を改善できるそれぞれのタスクを示している。
- issue を選択し、その指示に従って対応する
- 選択した issue に関わらず、プルリクエストを作成することで GitHub flow をもう一度演習することができる

----

### formerly: Instructions: Local Setup

Salvage the setup instructions from the commit #7d0ab749f156da9e1a9214bd07b96607f52622fc as same this document.

```
Instructions: Local Setup
1. Clone this repository to your machine with `git clone <URL>`.
2. Execute `script/setup` from your command line. This ensures all the right dependencies are installed.
3. Execute `script/server` from your command line. This spins up a local instance of the project.
4. You can view the local instance by navigating to http://localhost:4000/
```