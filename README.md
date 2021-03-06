Stocks
======

Experimental Android app with MVVM architecture. Purpose of this project is to explore different architectural
approaches and also "new age" technologies like Android Data Binding, RxJava, Lambdas, Retrofit, Dagger etc.

Main goals of this project
--------------------------
* Create good architecture with separate UI and business logic
* Write well readable, maintainable and testable code
* Follow OOP principles, single responsibility, DRY
* Avoid God classes (no way to have a class with 500+ lines)

This project uses
-----------------

* MVVM architecture
* Data binding
* Binding adapters
* RecyclerView
* ConstraintLayout
* RxJava
* Retrolambda
* OkHttp
* Retrofit
* GSON
* Glide
* LeakCanary

TODO
----
* 2 way binding
* Dagger
* Tests
* Proguard
* Travis

REST API
--------

* [http://dev.markitondemand.com/MODApis/](http://dev.markitondemand.com/MODApis/)

Examples:

* [http://dev.markitondemand.com/MODApis/Api/v2/Quote/json?symbol=INTC](http://dev.markitondemand.com/MODApis/Api/v2/Quote/json?symbol=INTC)
* [http://dev.markitondemand.com/MODApis/Api/v2/Lookup/json?input=Intel](http://dev.markitondemand.com/MODApis/Api/v2/Lookup/json?input=Intel)

Other APIs:

* https://developer.yahoo.com/yql/](https://developer.yahoo.com/yql/
* http://finance.yahoo.com/webservice/v1/symbols/INTC/quote?format=json
* http://finance.yahoo.com/webservice/v1/symbols/INTC,WDC/quote?format=json&view=‌​detail
* http://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20yahoo.finance.quotes%20where%20symbol%20IN%20(%22YHOO%22,%22AAPL%22)&format=json&env=http://datatables.org/alltables.env
* http://chart.finance.yahoo.com/z?s=INTC&t=5y&z=l&p=m50,m200
* https://www.quandl.com/api/v1/datasets/WIKI/INTC.json

Developed by
------------

[Petr Nohejl](http://petrnohejl.cz)

License
-------

    Copyright 2016 Petr Nohejl

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
