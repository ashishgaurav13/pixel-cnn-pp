https://packaging.python.org/tutorials/packaging-projects/

```
python3 setup.py sdist bdist_wheel
pip3 install dist/<wheel_name>
```

Inside python file:
```
import sys
sys.path.append(<folder which contains the pixelcnn folder>)
```
