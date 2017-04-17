## 汉语拼音定制输入方案，献给CHemperor！

基于[地球拼音](https://github.com/lotem/brise/blob/master/preset/terra_pinyin.schema.yaml)、[明月拼音](https://github.com/rime/brise/blob/master/preset/luna_pinyin.schema.yaml)、[明月拼音·筆畫輔助碼](https://github.com/rime-aca/schemata/blob/master/luna_pinyin_stroke/luna_pinyin_stroke.schema.yaml)及[中州韻之貓顏文字](https://github.com/hitigon/meow-emoji-rime/blob/master/meow_emoji.schema.yaml)制作，并为CH私人定制！

#### 定制方案的安装启用（仅适用于RIME for Window$。）
  1. [点我下载](http://pan.baidu.com/s/1i3GW9LV) 新版RIME安装包rime-gits-20151010-alpha，解压到某一硬盘分区的根目录（其他路径也可以，只是文件夹名不要有空格），进入rime-gits-20151010-alpha文件夹，以管理员权限运行「install」，接下来的提示均允许，之后「Ctrl + Shift」启动一次RIME；或[点我](https://bintray.com/lotem/rime/download_file?file_path=weasel-0.9.30.0-installer.exe)下载小狼毫0.9.30版，一路点「中」安装。
  2. [点我下载](http://git.oschina.net/erstern/haha_pinyin/repository/archive/master)，[或者是我](https://github.com/erstern/haha_pinyin/archive/master.zip) 下载哈哈拼音配置文件，解压。（两个下载地址分别为git.oschina与github，尽量同步推送，一般github以为准。）
  3. 若安装rime-gits-20151010-alpha（基于Google Input Tools），进入「C:\Users\Administrator\AppData\Roaming\Google\Google Input Tools\Rime」,把步骤2下载解压的配置文件全部复制进来。注意「Users」可能为中文「用户」，「AppData」可能为隐藏文件夹；若安装小狼毫（即旧版），点击「开始」或「Start」，找到「小狼毫输入法 -> 用户文件夹」。把步骤2下载解压的配置文件全部复制进来。
  4. 若安装rime-gits-20151010-alpha，点击「Ctrl + Alt + Delete」启动任务管理器，kill掉两个「GoogleInputTools」开头的进程（kill之后会自动活过来，点击一次「结束进程」即可），再次「Ctrl + Shift」启动RIME等待数秒，新配置生效；或重启计算机生效；若安装小狼毫，点击「开始 -> 小狼毫输入法 -> 重新部署」。
  5. 激活RIME输入法，按「Ctrl+`」，选择「哈哈拼音・何喝专享」即可开始使用。

#### 聲調
可以輸入符號 `- / < \` 作爲漢語拼音方案四種聲調，如輸入`a`，則字母分別轉寫爲``ā á â à``，其餘類推。

#### Tips
  - 下次只要（在中文模式下）直接輸入「vhaha」就能看到本方案最新版本地址，同樣方法下載並使配置生效即可。
  - 輸入「ü」時，在聲母「j q x」後，可用「u」替代，顯示時可自動轉寫爲「ü」；「l n」後仍以「v」表示。
  - 聲母爲「j q x」時，可以省略介母「i」，如「加」可簡化爲「ja」，「千」可簡化爲「qan」，「向」可簡化爲「xang」。
  - 切换为中文输入模式，句首点击字母「v」進入標點和其他符號輸入模式。
  - 在區分聲調的同時，无需切换，即可同时使用默認不帶聲調的[朙月拼音](https://github.com/lotem/brise/blob/master/preset/luna_pinyin.dict.yaml)方案。
  - 为不影响RIME 在 Excel 等軟件中快捷鍵的使用，取消默認的方案切換鍵[F4]。
  - 同時支持[朙月拼音·筆畫輔助碼](https://github.com/rime-aca/schemata/blob/master/luna_pinyin_stroke/luna_pinyin_stroke.schema.yaml)方案。輸入全拼後可以繼續鍵入五筆畫作爲輔助碼，如「木（mu）」，可輸入「muhspn」（mu+橫豎撇捺）確定字型。同時支持速成模式，即「全拼+五筆畫首筆+五筆畫末筆」，「木」爲「muhn」（mu+橫捺）。
  - 按「Ctrl+`」，选择「Easy English」可進入英文輸入模式，可以提示完整英文拼寫。
  - 支持颜文字！

#### Eggs
鍵入「v」後，輸入特定字符，有驚喜！

#### 歡迎提出寶貴建議
