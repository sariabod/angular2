API endpoints

OAUTH
[POST] http://api.czekmaet.com/oauth
requires: email='test@test.com', password='test', grant_type='password', client_id='testing'

returns a bearer token that must be attached to the header on all future requests.
Format: Authorization - Bearer xxxxxxxxxxxxxxx

api endpoint to test authentication
[GET] http://api.czekmaet.com/oauth/resource


