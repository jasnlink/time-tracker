# time_tracker
## Goal and purpose
A system that allows employers to track their employees' work time or for event organisers to track attendance. The employee scans a geolocated QR code when entering or leaving the workplace and the app logs and calculates work hours. This data can be sent straight to HR for payroll processing. Managers can know right away if someone did not come in or was late for work thanks to time sheet tracking.


## DB Planning
### tt_orgs

org_id

org_name


### tt_users

user_id

user_first_name

user_last_name

user_image

user_role

user_created_time

user_created_by

user_created_ip

username

password

org_id


### tt_locations

location_id

location_name

location_street

location_city

location_division

location_country

location_postcode

location_long

location_lat

location_radius

location_url

location_created_time

location_created_by

location_created_ip

org_id


### tt_log

time_id

time_date

time_start

time_end

time_duration

time_ip

time_long

time_lat

user_id

