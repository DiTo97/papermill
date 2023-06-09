# <a href="https://github.com/nteract/papermill"><img src="https://media.githubusercontent.com/media/nteract/logos/master/nteract_papermill/exports/images/png/papermill_logo_wide.png" height="48px" /></a>

An example of background notebook parametrization with Papermill using [nohup](https://www.gnu.org/software/coreutils/manual/html_node/nohup-invocation.html#nohup-invocation).

For more information on parametrization, see Papermill [official docs](https://papermill.readthedocs.io/en/latest/).

## Setup

```sh
git clone https://github.com/DiTo97/papermill.git
cd papermill
```

```sh
python -m venv venv
source venv/bin/activate
```

```sh
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Usage

```sh
./run_async_notebook.sh notebook.ipynb norway
```
