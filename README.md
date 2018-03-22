# 说明
配置文件config.py因涉及个人信息已删除,具体包含:
#### ------------- SQLAlchemy 相关----------------
DB_HOST =  
DB_PORT =  
DATABASE =  
DB_USERNAME =  
DB_PASSWORD =  
DB_URI = "mysql+pymysql://{username}:{password}@{host}:{port}/{db}" \
         "?charset=utf8".format(username=DB_USERNAME,
                                password=DB_PASSWORD, host=DB_HOST,
                                port=DB_PORT, db=DATABASE)
SQLALCHEMY_DATABASE_URI = DB_URI
SQLALCHEMY_TRACK_MODIFICATIONS = False
#### -------------- session相关 -------------------
SECRET_KEY = 
PERMANENT_SESSION_LIFETIME = 
#### ----------------- 常量 -----------------------
CMS_USER_ID = 
FRONT_USER_ID = 
#### ----------------- 邮箱 -----------------------
MAIL_SERVER = "smtp.126.com"
MAIL_PORT = 25
MAIL_USE_TLS = True
MAIL_USERNAME = 
MAIL_PASSWORD = 
MAIL_DEFAULT_SENDER = 
MAIL_DEBUG = False
#### ----------------- 阿里大于 -----------------------
ALIDAYU_APP_KEY = 
ALIDAYU_APP_SECRET = 
ALIDAYU_SIGN_NAME = 
ALIDAYU_TEMPLATE_CODE = 
#### ----------------- 短信验证码 -----------------
SMS_SALT = 
#### ----------------- UEditor -----------------
UEDITOR_UPLOAD_PATH = os.path.join(os.path.dirname(__file__), 'images')
UEDITOR_UPLOAD_TO_QINIU = False
UEDITOR_QINIU_ACCESS_KEY = 
UEDITOR_QINIU_SECRET_KEY = 
UEDITOR_QINIU_BUCKET_NAME = 
UEDITOR_QINIU_DOMAIN = 
#### -------------- flask-paginate ---------------
PER_PAGE = 10
#### -------------- Celery ---------------
CELERY_BROKER_URL = 'redis://redis:6379/0'
CELERY_RESULT_BACKEND = 'redis://redis:6379/0'


