## CSharp variables propias

You can use the [editor on GitHub](https://github.com/hugobepa/datosBasicosCSharp.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Tratamiento Datos propios CSharp

- data:text/html, <html contenteditable>
```markdown
### Object

- object a = 10; // int
- object b = new Customer(); // customer object
- object c = new Product(); // product object
- object d = "Jon"; // string
- string text = d.ToString();
- object e = new { Name = "Felipe", Age = 20 }; 

### Dynamic

- dynamic a = new Class();
- a.Age = 18;
- a.Name = "Jon";
- a.Product = new Product();
- a.Name; // read a string
- a.Age; // read an int
- a.Product.Name;

### Var

- var a = 10; // int
- var b = 10d; // double
- var c = "text"; // string
- var p = new Product()
- var personas = new List<Persona>();

- test? expression1 : expression

### List

- List<Persona> personas = new List<Persona>();
- List<int> iList = new List<int>();     iList.Add(2);     iList.Add(3);     
- List<int> list = new List<int>(array);
- List<int> primes = new List<int>(new int[] { 2, 3, 5 });
- string combindedString = string.Join(",", colors);
- string[] arr = colors.ToArray();
 
- ListDictionary list = new ListDictionary();
        - list.Add("dot", 1);
        - list.Add("net", 2);
        
- Hashtable hash = new Hashtable();
- hash.Add("dot", 1);

### Enum

     - public enum Color2  { Green = 10,  Orange = 20}
    - foreach(string s in System.Enum.GetNames(typeof(Color)))
    - Color favorite = Color.Blue;
   - .WriteLine("Favorite Color is {0}", favorite);
   
###  Path
  
  - string path2 = "\\\FileShare\\Directory\\file.txt";
  - string path2 = @"\\FileShare\Directory\file.txt";





