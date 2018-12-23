# S.M.A.R.T. Demo in .NET

![](Solution/S.M.A.R.T.-Demo\App.ico)

S.M.A.R.T. Demo is a simple and educative project to illustrate how to retrieve S.M.A.R.T. information from a hard drive using managed code in .NET. The source-code is written in VB.NET.

### Limitations

This tool does not pretend to be a professional S.M.A.R.T. information tool. 

Because the representation of the vendor-specific RAW values always needs further investigation, this tools has what we could consider a limitation in the meaning of being incapable to determine when a vendor-specific RAW value should be represented as a 64, 48 or 32 bit integer, because that is work of the developer itself. This is normal and understandable, because as I mentioned, this application does not pretend to be a professional tool.

For the reason being said, my implementation tries to facilitate this task by providing properties to show the RAW value in different representations. 

Anyways, almost all the vendor-specific RAW values are 32-bit integer values, which is the default kind of value represented in the user-interface of this tool.

### Screenshots:

![](Preview/Screenshot-1.png)

![](Preview/Screenshot-2.png)

### Donations

Any code within the namespace "DevCase" are freely distributed as part of "DevCase for .NET Framework" source-code (previously known as "ElektroKit Framework for .NET").
 
Maybe you would like to consider to buy this powerful set of libraries to support me. You can do loads of things with my APIs for a big amount of diverse thematics, not only related to devices and so.
 
Here is a link to the purchase page:
https://codecanyon.net/item/elektrokit-class-library-for-net/19260282

Thank you.