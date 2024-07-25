# Notes

## Making layers

```
pip install --platform manylinux2014_x86_64 --python 3.8 --implementation cp --target python --only-binary=:all: --upgrade <my-packages>
zip -vr <my-packages>.zip ./python
```
Upload into aws lambda layers. Enjoy.
