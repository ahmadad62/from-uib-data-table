# Basic Data Exercises

## Exercise: Table 2

**Instructions**:

1.  Create a basic HTML page with all important elements.
2.  Look at the mockup file and create the following table with 3 columns.

| Company                      | Contact          | Amount |
| ---------------------------- | ---------------- | ------ |
| Alfreds Futterkiste	         | Maria Anders	    |     45 |
| Centro comercial Moctezuma	 | Francisco Chang  |     45 |
| Ernst Handel                 | Roland Mendel    |     45 |
| Island Trading               | Helen Bennett	  |     45 |
| Laughing Bacchus Winecellars | Yoshi Tannamuri  |     45 |
| Magazzini Alimentari Riuniti | Giovanni Rovelli |     45 |
| Total                        |                  |    210 |

3.  Style it with zebra stripes using pseudo child selectors.
4.  Do NOT use deprecated HTML attributes. Style using CSS.

!["mockup-image"](/image/mockup.png)




* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

table {
  width: 100%;
  height: 30%;
  border: 5px solid rgb(242, 236, 236);
}
tbody tr:nth-child(odd){
    background-color: antiquewhite;

}