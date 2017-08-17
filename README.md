CarRegistration
===========

This is an API Wrapper for Python for the VehicleRegistrationApi.com API
which allows you to get car data from it's number plate in many countries
across the globe, from the USA, Europe, Australia, and Africa.

An account username and password is required from [VehicleRegistrationApi.com](http://www.VehicleRegistrationApi.com)

The fourth parameter is an endpoint, which is "Check" for the UK,
or "CheckFrance", "CheckItaly" etc. for respective countries.
USA / Australia are not currently supported.

# Installation
```python
 easy_install CarRegistration
```

# Usage
```python
 from CarRegistration import *
 CarRegistration("BL64JTZ","***YOUR USERNAME***","***YOUR PASSWORD***","Check")
```

# Sample output

```json
{u'RegistrationYear': u'2015', u'CarModel': {u'CurrentTextValue': u'208'}, u'NumberOfDoors': {u'CurrentTextValue': u'3'}, u'EngineSize': {u'CurrentTextValue': u'1397CC'}, u'Description': u'2015 Peugeot 208 Active Hdi 70, 1397CC Diesel, 3DR, Manual', u'ABICode': u'39125401', u'Transmission': {u'CurrentTextValue': u'Manual'}, u'ImageUrl': u'http://www.regcheck.org.uk/image.aspx/@UGV1Z2VvdCAyMDg=', u'CarMake': {u'CurrentTextValue': u'Peugeot'}, u'Immobiliser': {u'CurrentTextValue': u''}, u'MakeDescription': u'Peugeot', u'IndicativeValue': {u'CurrentTextValue': u''}, u'VehicleInsuranceGroup': u'35', u'ModelDescription': u'208', u'FuelType': {u'CurrentTextValue': u'Diesel'}, u'NumberOfSeats': {u'CurrentTextValue': 5}, u'DriverSide': {u'CurrentTextValue': u'RHD'}}
```
