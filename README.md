# Learning Performance Testing

This a peak learning performance testing project. Where I'm using five http requests to perform my task. Besides this I'm using three listener to see the result & report of the task. Depending on the circumstances, I have also used user defined variables, http header manager and json extractor. To see the graph of endurence testing and spike testing I've also attached a ultimate thread group.
```console
npm install -g newman-reporter-htmlextra
```

## Screenshots
### Thread Group
![Thread Group](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Thread%20Group.png?raw=true)

### User Defined Variables
![User Defined Variables](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/User%20Defined%20Variables.png?raw=true)

### Create Booking
![Create Booking](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/createBooking.png?raw=true)

### Get Booking
![Get Booking](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/getBooking.png?raw=true)

### Access Token Authentication
![Access Token Authentication](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/accessTokenAuthentication.png?raw=true)

### Update Booking
![Update Booking](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/updateBooking.png?raw=true)

### Delete Booking
![Delete Booking](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/deleteBooking.png?raw=true)

### View Results Tree
![View Results Tree](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/View%20Results%20Tree.png?raw=true)

### Summary Report
![Summary Report](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Summary%20Report..png?raw=true)

### Aggregate Report
![Aggregate Report](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Aggregate%20Report.png?raw=true)

### Endurance Testing
![Endurance Testing](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Endurance%20Testing.png?raw=true)

### Spike Testing
![Spike Testing](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Spike%20Testing.png?raw=true)

## Command for html report
```console jmeter -n -t project1_t1200.jmx -l report\project1_t1200.jtl ```
- jmeter -g report\project1_t1200.jtl -o report\project1_t1200.html
### Test and Report information for 1200 threads
![Test and Report information](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Test%20and%20Report%20information_t1200.png?raw=true)

![Statistics](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Statistics_t1200.png?raw=true)
#### Total transaction per Second(tps)
![tps](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/tps_t1200.png?raw=true)

## Command for html report
- jmeter -n -t project1_t1300.jmx -l report\project1_t1300.jtl
- jmeter -g report\project1_t1300.jtl -o report\project1_t1300.html
### Test and Report information for 1300 threads
![Test and Report information](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Test%20and%20Report%20informatin_t1300.png?raw=true)

![Statistics](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Statistics_t1300.png?raw=true)
#### Total transaction per Second(tps)
![tps](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/tps_t1300.png?raw=true)

## Command for html report
- jmeter -n -t project1_t1400.jmx -l report\project1_t1400.jtl
- jmeter -g report\project1_t1400.jtl -o report\project1_t1400.html
### Test and Report information for 1400 threads
![Test and Report information](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Test%20Report%20and%20information_t1400.png?raw=true)

![Statistics](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/Statistics_t1400.png?raw=true)
#### Total transaction per Second(tps)
![tps](https://github.com/SaifullaKamran/Learning-Performance-Testing/blob/master/Project%20Pictures/tps_t1400.png?raw=true)








## Summary
1200 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 96 And Total Concurrent API requested: 6000.

1300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 108 And Total Concurrent API requested: 6500.

1400 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 116 And Total Concurrent API requested: 7000.


While executed 1400 concurrent request, found  99.81% request got connection and error rate is 0.19% which is less than 1% 

Summary: Server can handle almost concurrent 6900 API call with almost zero (0) error rate.

Please find the details report from the attachment and  let me know if you have any further queries. 









