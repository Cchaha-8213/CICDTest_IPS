# CICDTest_IPS

# Jenkins node remote failed:
 #_1. Jenkins node的SSH是使用Java去remote，所以remote的PC需要裝Java
 #_2. cmd不能設定成英文模式(chcp 437)，否則remote過去時會回覆received junk message


# 若要使github hook可以連接到Jenkins，必須利用Ngrok將Jenkins server轉成domain IP再到webhook設定連結
# https://zoejoyuliao.medium.com/%E9%80%8F%E9%81%8E-github-webhook-%E8%A7%B8%E7%99%BC%E6%9C%AC%E5%9C%B0-jenkins-pipeline-%E8%AE%93%E4%BD%A0-push-code-%E5%88%B0-github-%E5%B0%B1%E6%9C%83%E8%87%AA%E5%8B%95%E8%B7%91-ci-cd-7c4bd7a22446
