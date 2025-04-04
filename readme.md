first : aws configure
then give access key, secret key. your region ( default: ap-southeast-1), output format ( default to JSON) to json/text/table...

mkdir service-infra
cd service-infra

sudo apt update
sudo apt install python3.8-venv -y

pulumi new aws-python
