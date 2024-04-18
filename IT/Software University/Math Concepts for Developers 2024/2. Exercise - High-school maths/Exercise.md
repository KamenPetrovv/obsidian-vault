[IEEE-754 - Floating Point Precision Math problems](https://en.wikipedia.org/wiki/IEEE_754)

## Markdown
```
**bold**
*italic*
~~scratched~~
```
**bold**
*italic*
~~scratched~~

```
1. First
2. Second
* bullets
* bullets
	+ Unordered
    - list
```
1. First
2. Second
* bullets
* bullets
	+ Unordered
    - list

Pasted
![[Pasted image 20240414092836.png]]
Linked
![Alt text](http://i.imgur.com/dkY1gph.jpg)

### [Table Generator](https://www.tablesgenerator.com/markdown_tables)

```
| Cell1 | Cell2 | Cell3 |
|-------|-------|-------|
| 1.1   | 1.2   | 1.3   |
| 2.1   | 2.2   | 2.3   |
| 3.1   | 3.2   | 3.3   |
```

| Cell1 | Cell2 | Cell3 |
|-------|-------|-------|
| 1.1   | 1.2   | 1.3   |
| 2.1   | 2.2   | 2.3   |
| 3.1   | 3.2   | 3.3   |

```python
def awesome(x):
	return x**2;
```

## [Numpy broadcasting](https://numpy.org/doc/stable/user/basics.broadcasting.html)

Broadcasting provides a means of vectorizing array operations so that looping occurs in C instead of Python. It does this without making needless copies of data and usually leads to efficient algorithm implementations. There are, however, cases where broadcasting is a bad idea because it leads to inefficient use of memory that slows computation.

When operating on two arrays, NumPy compares their shapes element-wise. It starts with the trailing (i.e. rightmost) dimension and works its way left. Two dimensions are compatible when

1. they are equal, or
    
2. one of them is 1.
    

If these conditions are not met, a `ValueError: operands could not be broadcast together` exception is thrown, indicating that the arrays have incompatible shapes.

## MatplotLib

```
plt.gca()
``` 
Gets the main target figure

## Trigonometry
Unit circle - тригонометрична окръжност
![[Pasted image 20240415103751.png]]

Radian - _the central angle of an arc with length equal to the circle's radius_ and 1rad≈57.296∘1rad≈57.296∘.
![[Pasted image 20240415103938.png]]
 In order to convert between radians and degrees, you can use the relations:
  [deg]=180/𝜋.[rad]
  [rad]=𝜋/180.[deg]

 This can be done using `np.deg2rad()` and `np.rad2deg()` respectively.

