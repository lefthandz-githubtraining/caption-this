# Day 2: Merge Conflicts

### In Class Activities:

#### Finish Workflow
- Work in the same repository as Day 1, "caption this"
- We opened pull requests yesterday; Today we make more changes to the same branches
- Merging, ending in glorious merges and a reveal of the final project. :sparkles:

#### Merge Conflicts
- Introduced the concept of merge conflicts:
  - Why merge conflicts happen
  - How Git handles merge conflicts
  - How we (the humans) handle merge conflicts
- Synchronously, we partner up and created merge conflicts  

### After Class Activities:

#### Resolve the rest of the merge conflicts
- We've set up some open pull requests with merge conflicts for you :open_mouth:
  - _Every person_ has their own repository. Each person should fix the merge conflicts in their own repo. It wil be called `github.com/githubschool/conflict-practice-username`, with username being your actual username.
  - We won't make you turn in your homework, but we will run a script to see if the activities are completed later. :wink:
- Work to resolve the merge conflicts in the conflicts repository.
  - Don't remember the steps from class? No worries. As a general rule of thumb, here is a starting point:
  - Working locally, merge `master` into the feature branch.
  - When you see there's a conflict, that's OK! Type `git status` to verify which file has the conflict.
  - Open that file in your text editor, and look for the merge conflict markers. (`<<<<<<<`, `=======`, `>>>>>>>`)
  - Both branches' versions of code are present - pick which one you want to keep, and save the changes.
  - Add and commit the saved changes to resolve the merge conflict.
  - Push the feature branch up to the remote, and see the resolution in the pull request.

----

# [ja] Day 2: マージコンフリクト

### クラスでの演習:

#### ワークフローを完了する

- Day 1 と同じリポジトリ "caption this" で作業する
- 前日作成したプルリクエストと同じブランチにさらに変更を加えていく
- Merging, ending in glorious merges and a reveal of the final project. :sparkles:

#### マージコンフリクト

- マージコンフリクトのコンセプトについて紹介する
  - なぜマージコンフリクトが起きるのか
  - Git はどうマージコンフリクトを対処するのか
  - 私たち（人間）がどうマージコンフリクトを対処するか
- 同時に、パートナーを組んでマージコンフリクトを作る

### クラスでの演習ののち:

#### マージしたコンフリクトの残りを解決する

- 受講者にむけてマージコンフリクトを含むプルリクエストを作成する :open_mouth:
  - _全員_ にそれぞれのリポジトリを用意する。受講者はそれぞれのリポジトリでマージコンフリクトを解消する。リポジトリは `conflict-practice-USERNAME` の命名パターンで用意される。
  - ホームワークにはしないが、もし後に課題が完了しているかスクリプトを実行して確認する :wink:
- この conflicts repository で、マージコンフリクトを解消していく
  - class repository からの手順を覚えていなくても大丈夫、一般的な経験則として、最初のポイントはこれら
  - ローカルで作業し、 feature branch に `master` ブランチをマージする
  - コンフリクトを見つけても大丈夫、 `git status` を実行してどのファイルでコンフリクトが発生しているか確認する
  - テキストエディタでそのファイルを開き、コンフリクトマーカー (`<<<<<<<`, `=======`, `>>>>>>>`) を確認する
  - 両方のブランチのコードが表示されるので、保持したい方を残し、保存する
  - マージコンフリクトを解消するため、その保存した変更をステージに追加し、コミットする
  - その feature branch をリモートにプッシュし、プルリクエスト上でマージコンフリクトが解消されたことを確認する

----

References:

- https://docs.github.com/ja/github/collaborating-with-pull-requests/addressing-merge-conflicts