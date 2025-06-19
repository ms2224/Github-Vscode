# Github-Vscode
VSCodeでのGithubのバージョン管理のためのメモ

## Githubでリポジトリを作成する

## Gitのインストール（Windows）
https://gitforwindows.org/ からインストール

## Gitのインストール（Linux）
```
sudo apt update
sudo apt install git
```
でインストール

## ユーザー名とメールアドレスの登録
```
git config --global user.name ユーザー名
git config --global user.email メールアドレス
```
でユーザー名とメールアドレスを登録する．
メールアドレスを非公開にしたい場合は，https://github.com/settings/emails より ```数字+ユーザー名@users.noreply.github.com``` を使う．

## VSCodeでの操作
### 1. VSCodeで任意のフォルダを開く
### 2. ソース管理を開いて ```リポジトリを初期化する``` を行う
  ![image](https://github.com/user-attachments/assets/72a0f321-e3dd-4da8-9e4d-5f485c89bfe7)
### 3. ```クローン``` をクリック
  ![image](https://github.com/user-attachments/assets/1d2609e4-0236-4607-b7dc-bf36bb646eb9)
### 4. ```Githubから複製``` をクリック
  ![image](https://github.com/user-attachments/assets/10a59046-f3bc-4b1e-954f-2c0228ff8e3d)
### 5. 4 を行うとブラウザでGithubとの連携ページが開かれるので連携を行う
  ![image](https://github.com/user-attachments/assets/a5313004-40b7-49d4-adb3-0b7c3ab71e9f)
### 6. 連携が行えると自分のアカウントのリポジトリから選択できるので任意のリポジトリを選択
  ![image](https://github.com/user-attachments/assets/1967cfd4-1415-4933-a19f-edd454a4edb7)
### 7. 複製したリポジトリを開く
  ![image](https://github.com/user-attachments/assets/ff5d972d-9f93-485a-90a3-68a5d309dc4e)
### 8. リポジトリを複製したフォルダ内のファイルがこのように表示され、バージョン管理したいファイルの ```＋ボタン``` をクリックしてステージする
  ![image](https://github.com/user-attachments/assets/7e41d9bd-0a36-47ce-8e27-d99eee6968f3)
### 9. 名前を付けてコミットをクリックすることでローカルでバージョンが管理できる
  ![image](https://github.com/user-attachments/assets/a30c10e8-29a9-46b4-9aea-f20a75b7ee03)
### 10. ```変更の同期``` でリモートリポジトリで管理する
  ![image](https://github.com/user-attachments/assets/c77c382b-7179-44e9-9586-b9debb9058b1)
### 11. 10を行うとこのようなポップアップが出るので ```OK``` をクリック
  ![スクリーンショット 2025-06-19 001905](https://github.com/user-attachments/assets/faba748a-5daf-4fd2-9a0f-738a6b0290bc)
### 12. コミットしたファイルの内容が変更されると ```M``` と表示される
  ![image](https://github.com/user-attachments/assets/c50f482c-6aec-461f-8d91-c06bc775e7c0)
### 13. バージョンを管理したいタイミングで ```9~11``` を行い適宜バージョンを管理する
### 14. ブランチを用意すると便利
