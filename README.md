# UPJV-API
Endpoints de l'API de l'application MonUPJV

Base url : https://api.appscho.com/upjv/
Endpoints:
- login (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'password'})
- webviews/adminfile (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- webviews/ent (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- news (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- grades             (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- career/events      (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- career/offers      (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- locations          (headers={'X-Appscho-Token':'token'}) Base url : https://my.appscho.com/api/upjv/
- webviews/missions  (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- planning           (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token'})
- idcard/picture     (headers={'X-Appscho-Token':'token'})
- idcard/pubkeys
- idcard/generate    (headers={'X-Appscho-Token':'token'})
- whoami             (headers={'X-Appscho-Id':'studentNumber', 'X-Appscho-Token':'token', 'X-Appscho-Timestamp':?, 'X-Appscho-Url':?})
