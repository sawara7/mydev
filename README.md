# windows

## vscode
https://code.visualstudio.com/download

## git
https://git-scm.com/

## github cli
https://cli.github.com/

### ログイン
gh auth login

コミットするときにuserとemail
git config --global user.email sawara7+dev@gmail.com
git config --global user.name sawara7

### クローン
gh repo clone sawara7/firebase-utils-server

## node.js
https://nodejs.org/ja/

## mongodb
https://www.mongodb.com/try/download/community?tck=docs_server

## Google Cloud SDK
https://cloud.google.com/sdk/docs/install-sdk?hl=ja

gcloud compute ssh --project fxbot-c80cd --zone asia-northeast2-a fxbot-1

# PowerShell 2.0
### PowerShellのセキュリティポリシーの変更
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned

### node.jsをバックグラウンドで実行する(Windows)
Start-job -Name "bot-xxx" {node .}
Get-job
Remove-job

