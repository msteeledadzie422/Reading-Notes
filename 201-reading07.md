# Domain Modeling

1. A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

# HTML Basics

1. Reasons to stay away from using a Table as a layout for an HTML page:
    - Layout tables reduce accessibility for visually impaired users: Screenreaders, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screenreaders' output will be confusing to their users.
    - Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.
    - Tables are not automatically responsive: When you use proper layout containers (such as <header>, <section>, <article>, or <div>), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

2. <td>: table data, creates a cell
   <tr>: table row, creates a table row
   <th>: table header, a table header
     
# Introducing Constructors
     
1. A Constructor Function defines the "shape" of an oboject - the set of methods and the properties it can have - and then create as many objects as we like, just updating the values for the properties that are different.
     
2. When used in a constructor, "this" is binded to the new object so you can refer to this in your constructor code.
     
# Object Prototypes Using a Constructor
     
Every object has a prototype, and elements of that prototype can be referred to to create new objects!
