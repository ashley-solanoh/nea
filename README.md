# nea
trabajo para el GCSE

## How to set up the work environment

* Create the work directory

<pre>
mkdir workspace
</pre>

* Clone the git repository

<pre>
cd workspace/
git clone  https://github.com/ashley-solanoh/nea.git
</pre>

* Create a virtual environment

<pre>
cd nea
mkdir .pyenv
python3.6 -m venv .pyenv
</pre>

* Activate the vritual environment

<pre>
source .pyenv/bin/activate
</pre>

* Once activated, the prompt should say the following:
<pre>
(.pyenv) [ascloud@ashdev-py nea]$
</pre>

* Install Flask

<pre>
pip install Flask
</pre>

* Start the flask server

<pre>
python hello.py
</pre>

* Navigate to the server using the following URL

<pre>
http://192.168.0.82:5000/hello
</pre>














