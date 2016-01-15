# cybernetic-organism

Machine learning tutorials and resources

### Installing GraphLab Create

1. Register an **email address** and **product key** at [Dato](http://www.dato.com).
2. Follow instructions or install via ```pip``` with the following.
3. **Note:** GraphLab Create requires Python 2.7. You may need to specifiy the path to your Python 2.7 binary if you run multiple versions of Python or have symlinks pointing to an incompatible Python version.

Create a virtualenv.

```
$ virtualenv dato-env
$ source dato-env/bin/activate
$ pip install --upgrade pip
```

(Optional) Install IPython and IPython Notebook .

``` 
$ pip install "ipython[notebook]"
```

Install GraphLab Create.

```
$ pip install --upgrade --no-cache-dir https://get.dato.com/GraphLab-Create/1.6.1/**registered email**/**product key**/GraphLab-Create-License.tar.gz 
```

Using GraphLab Create with Python.

```
import graphlab
```
