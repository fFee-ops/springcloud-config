# springcloud-config

bootstrap.yml的优先级比application.yml高，所以在3355，3366就应该要写bootstrap.yml，
因为要先去bootstrap.yml找到该从哪个地方拉取配置中心的yml
