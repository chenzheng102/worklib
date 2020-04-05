#例子
sender  = "" #发送者
receivers = ["",""]
title = "这是一个标题啊"
host = "smtp.qq.com"

user = "743872668@qq.com"
pwd = ""

email_config = {
    "host":"smtp.qq.com"
    ,"port":465
    ,"sender":sender
    ,"pwd":pwd


}
send_user = []
body_type = "plain"
body = "z设置"
body = {"receivers":receivers
        ,"title":title
        ,"body":body
        ,"type":body_type
        }
send_email(email_config,body)