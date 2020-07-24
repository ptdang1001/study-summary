# 20200523@path operation
```python
#add current file's path to sys.path
sys.path.append(os.path.dirname(os.path.abspath(__file__)))
#add current run path to sys.path
sys.path.a(os.path.dirname(os.getcwd()))
```