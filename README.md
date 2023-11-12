# Helm 기반 마크서버

values-minecraft.yaml을 먼저 배포해서 마인크래프트 서버들을 띄움


지금 설정은 2개의 마인크래프트 서버가 띄워짐


그 후 해당 clusterIP를 values-minecraft-proxy.yaml에 minecraftProxy.config servers에서 서버 정의하는 곳에 넣어서 실행


마인크래프트에 들어가서 /server [설정한 서버이름] 해서 잘 실행되는 지 확인