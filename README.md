# sqlalchemy-challenge
Sqlalchemy challenge
## Adjustments and corrections made with the Xpert Learning Assistant
#### The addition of ".scalar() function" on the following snipet: recent_date = session.query(func.max(Measurement.date)).scalar()
#### The addition of "'%Y-%m-%d'" on the strptime and strftime functions
#### Addition of the "temp_count.index," on the snipet: df_freq_temp = pd.DataFrame({'Value': temp_count.index, 'Count': temp_count.values})
#### Corrections made on imports of some of the functions on the following snipet: import sqlalchemy
#### from sqlalchemy.ext.automap import automap_base
#### from sqlalchemy.orm import Session
#### from sqlalchemy import create_engine, func, MetaData, select, desc
#### from datetime import datetime, timedelta
