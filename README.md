git clone https://github.com/yourusername/custom-sms-api.git
cd custom-sms-api
pip install -r requirements.txt npm install
cp .env.example .env
python manage.py migrate npm run migrate
{
  "to": "+88{1234567890}",
  "message": "Hello, this is a test message!"
}
curl -X POST http://localhost:PORT/api/send-sms \
  -H "Content-Type: application/json" \
  -d '{"to": "+1234567890", "message": "Hello, this is a test message!"}'
  pytest
  npm test
  
