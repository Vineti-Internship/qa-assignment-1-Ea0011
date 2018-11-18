**For USA By Air the delivery costs are: lower 10kg - 4000 AMD per 1kg
10kg and more - 3500 AMD per 1kg**

**For USA BY Sea the delivery costs are: 1kg - 1200 drams
Minimum up to 10kg – 12000 drams**

**For Russia the delivaery costs are: 1kg - 2000 drams**

**For UK and China the delivery costs are: 1kg - 4000 drams**

**If specifying the size of the parcel the maximum of weight and volumetric weigth is taken**  
- **International formula for calculating the volumetric weight: Length * width * height /6000 (cm/kg)**  

- **Note** It seems the calculator does not react to floating point numbers. I guess this is a Fail.


| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With USA Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check USA Flag <br> <br> 3. Check Online Shopping <br> <br> 4. Check By Air <br> <br> 5. Enter The Weight 	| Server Side Should Work Correctly 	| 0 	| 0 	| 400 	| Failed 	|

| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With USA Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check USA Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Check By Air <br> <br> 5. Enter The Weight  	| Server Side Should Work Correctly 	| 1 	| 4000 	| 4000 	| Passed 	|

| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With USA Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check USA Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Check By Air <br> <br> 5. Enter The Weight 	| Server Side Should Work Correctly 	| 10 	| 35000 	| 35000 	| Passed 	|


| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With USA Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check USA Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Check By Sea <br> <br> 5. Enter The Weight 	| Server Side Should Work Correctly 	| 4 	| 12000 	| 12000 	| Passed 	|

| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With USA Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check USA Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Check By Sea <br> <br> 5. Enter The Weight 	| Server Side Should Work Correctly 	| 15 	| 18000 	| 18000 	| Passed 	|



| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (cm/kg) 	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------        	|-----------------	|---------------    |--------	|
| Shipping Calculator 	|  Check Response On Entering Data With USA Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check USA Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Check By Sea <br> <br> 5. Enter The Weight and Size 	| Server Side Should Work Correctly 	| Size <br> 300 X 30 X 30 <br> <br> Weight: <br> 12 	| 54000 	| 54000 	| Passed 	|

| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg) 	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With Russia Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check Russia Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Enter The Weight 	| Server Side Should Work Correctly 	| 0 	| 0 	| 2000 	| Failed 	|


| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg) 	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With Russia Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check Russia Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Enter The Weight 	| Server Side Should Work Correctly 	| 20 	| 40000 	| 40000 	| Passed 	|



| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (cm/kg) 	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------        	|-----------------	|---------------    |--------	|
| Shipping Calculator 	|  Check Response On Entering Data With Russia Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check Russia Flag <br> <br> 3. Check Online Shopping  <br> <br> 4. Enter The Weight and Size 	| Server Side Should Work Correctly 	| Size <br> 1000 X 100 X 10 <br> <br> Weight: <br> 20 	| 33333 	| 33333 	| Passed 	|

| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With UK Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check UK Flag <br> <br> 3. Check Online Shopping <br> <br> 4. Enter The Weight 	| Server Side Should Work Correctly 	| 0 	| 0 	| 400 	| Failed 	|


| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With UK Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check UK Flag <br> <br> 3. Check Online Shopping <br> <br> 4. Enter The Weight 	| Server Side Should Work Correctly 	| 10 	| 40000 	| 40000 	| Passed 	|


| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With China Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check China Flag <br> <br> 3. Check Online Shopping <br> <br> 4. Enter The Weight 	| Server Side Should Work Correctly 	| 0 	| 0 	| 400 	| Failed 	|



| Test Scenario 	|  Test Case 	| Test Steps 	| Pre Conditions 	| Test Data (kg)	| Expected Result 	| Actual Result 	| Status 	|
|---------------------	|--------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------	|-----------	|-----------------	|---------------	|--------	|
| Shipping Calculator 	|  Check Response On Entering Data With China Chosen 	|  1. Click The Calculator Icon <br> <br> 2. Check China Flag <br> <br> 3. Check Online Shopping <br> <br> 4. Enter The Weight 	| Server Side Should Work Correctly 	| 10 	| 40000 	| 40000 	| Passed 	|
