---
layout: global
title: UDFs (User-Defined Functions)
displayTitle: UDFs (User-Defined Functions)
license: |
  Licensed to the Apache Software Foundation (ASF) under one or more
  contributor license agreements.  See the NOTICE file distributed with
  this work for additional information regarding copyright ownership.
  The ASF licenses this file to You under the Apache License, Version 2.0
  (the "License"); you may not use this file except in compliance with
  the License.  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
---

User-Defined Functions (UDFs) are a feature of Spark SQL that allows users to define their own functions when the system's built-in functions are not enough to perform the desired task. To use UDFs in Spark SQL, users must first define the function, then register the function with Spark, and finally call the registered function. The User-Defined Functions can act on a single row or act on multiple rows at once. Spark SQL also supports integration of existing Hive implementations of UDFs, UDAFs and UDTFs.

 * [Scalar User-Defined Functions (UDFs)](sql-ref-functions-udf-scalar.html)
 * [User-Defined Aggregate Functions (UDAFs)](sql-ref-functions-udf-aggregate.html)
 * [Integration with Hive UDFs/UDAFs/UDTFs](sql-ref-functions-udf-hive.html)
