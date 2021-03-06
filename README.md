# AwesomeSerializer

NuGet package:
* [AwesomeSerializer](https://preview.nuget.org/packages/AwesomeSerializer/1.0.1)

PM> Install-Package AwesomeSerializer -Version 1.0.1

## Usage
We have two controllers, ProductController and CategoryController.

Decorate your controller with:
```C#
[AwesomeSerializer.Serializers.AwesomeSerializer(typeof(YourCustomResolver))]
```

![alt text](https://github.com/Damian-Pumar/AwesomeSerializer/blob/master/Example/Images/CategoryController.PNG)
![alt text](https://github.com/Damian-Pumar/AwesomeSerializer/blob/master/Example/Images/ProductController.PNG)

AwesomeSerializer allows you to serialize properties depending on a particular controller using custom resolvers

![alt text](https://github.com/Damian-Pumar/AwesomeSerializer/blob/master/Example/Images/ProductResolver.PNG)
![alt text](https://github.com/Damian-Pumar/AwesomeSerializer/blob/master/Example/Images/CategoryResolver.PNG)

## Results
Get api/product .   return:

![alt text](https://github.com/Damian-Pumar/AwesomeSerializer/blob/master/Example/Images/ResultProductController.PNG)

Get api/category .  return:

![alt text](https://github.com/Damian-Pumar/AwesomeSerializer/blob/master/Example/Images/ResultCategoryController.PNG)

Thanks!


