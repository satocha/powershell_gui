# powershell_gui
## powershellでGUI表示
GUI表示ができるpowershellの自作関数をまとめてみました。基本、NASに置いて、いろんなマシンから使うことを考えているので、必要なライブラリなどはパッケージ管理ではなく、どこかのパスにDLLを置いてある前提で作っています。
1. FileFolderDialog.ps1  
windows.formsのOpenFileDialogではフォルダが選択できないこと、何をしてほしいかユーザに伝えるにはタイトルにいれるしかないことなど不満があったので作りました。  
WindowsAPICodePackを使っているのでdllを取ってくる必要があります。  
2.aaa  
