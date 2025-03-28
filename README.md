📌 Flask Number API
This Flask application fetches numbers from an external API and maintains a sliding window of the last 10 unique numbers, calculating their average.

🚀 Setup
Install dependencies:

sh
Copy
Edit
pip install flask flask-cors requests
Run the server:

sh
Copy
Edit
python app.py
Access API:

bash
Copy
Edit
http://127.0.0.1:5000/numbers/<type>
<type> can be p, f, e, r.

🔧 Features
Fetches numbers from an external API.

Removes duplicates and maintains the last 10 numbers.

Returns JSON with previous & current states and average.

🛠 Debugging
Increase API timeout in fetch_numbers().

Print responses for debugging.

Use mock data if API fails.

