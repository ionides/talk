
Here's how Python was set up

```
cd ~/git/talk/queens25
rm -rf .venv
python3.12 -m venv .venv
source ~/git/talk/queens25/.venv/bin/activate
pip install --update pip
pip install -r requirements.txt

mk -B slides.pdf

```
