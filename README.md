### Algorithm for file updates in Python

## Project description
I am a part of a cybersecurity team at a healthcare facility. My main task is to ensure that only authorized employees have access to SPII, based on their IP addresses. I achieve it through a designated list of IP addresses, `allow_list.txt`, and an algorithm that removes IP addresses of machines of employees who have authorization no more.

### Summary
In this overview, I develop an algorithm to keep the list of authorised IP addresses to access SPII at the healthcare facility current. First, I import a designated list of IP addresses, `allow_list.txt` and make necessary modifications to prepare it for automation such as parsing and conversion into a list and a string through the `.read()` and the `.open()` commands. Next, I iterate through the `ip_addresses` file with a  for loop to designate IP addresses for deletion. After that, I  remove all of the IP addresses  from the `allow_list`  by means of the `.remove()` function. In the end, I record the changes made by the `.remove()` function with the `.write()` method.
