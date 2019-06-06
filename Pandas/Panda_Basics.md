# Introduction
There are two core objects in `pandas`: the **DataFrame** and the **Series**.
  ## DataFrame
```
pd.DataFrame({'Yes': [50, 21], 'No': [131, 2]})
```
![image](https://user-images.githubusercontent.com/47073386/59037910-c2756b80-88a4-11e9-9431-1f889befb1c0.png)

```
pd.DataFrame({'Bob': ['I liked it.', 'It was awful.'], 'Sue': ['Pretty good.', 'Bland.']})
```
![image](https://user-images.githubusercontent.com/47073386/59038126-184a1380-88a5-11e9-918e-ed78a3dc54cc.png)

We can assign values to it by using an `index` parameter in our constructor:

```
pd.DataFrame({'Bob': ['I liked it.', 'It was awful.'], 
              'Sue': ['Pretty good.', 'Bland.']},
             index=['Product A', 'Product B'])
```
![image](https://user-images.githubusercontent.com/47073386/59038294-6232f980-88a5-11e9-8abc-762222f9771a.png)
