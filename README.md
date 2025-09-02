# DEVOPS-essentiall

change permisssion (private file in windows)

icacls cicd.pem /inheritance:r
icacls cicd.pem /grant %USERNAME%:R
