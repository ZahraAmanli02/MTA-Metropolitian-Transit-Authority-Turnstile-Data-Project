
# MTA (Metropolitan Transit Authority) Turnstile Data Project

I have analyzed the "MTA (Metropolitan Transit Authority) Turnstile Data"

In the city of New York, commuters use the Metropolitan Transportation Authority (MTA) subway system for transportation. Millions of people use this system every day;

For this purpose, they place street teams at the entrances of metro stations. Street teams collect the e-mail addresses of people they can reach and send free tickets to those who register for their events.

So the main purpose of analyzing this data is to optimize the placement of street teams. "They want to reach the maximum number of people who can participate in the event and contribute to their goals by using MTA metro data, which they are sure can be obtained from the city free of charge."

This project was developed in a Jupyter Notebook using Python, leveraging libraries such as NumPy and Pandas for data analysis, and Matplotlib and Seaborn for data visualization.




•	Numpy: it contains many functions for numerical computation (vectors, matrices, polynomials, etc.).

•	Pandas: it allows to manipulate and analyze data (dataframes).

•	Matplotlib: it allows to trace and visualize data in the form of graphs.

•	Seaborn: it complements Matplotlib by providing attractive statistical graphics.



## The data contains the following fields:

- C/A - Control Area name/Booth name. This is the internal identification of a booth at a given station.
- Unit - Remote unit ID of station.
- SCP - Subunit/Channel/position represents a specific address for a given device.
- STATION - Name assigned to the subway station by operations planning. This name is used in all references to stations, as well as in debit/credit purchase receipts, and customer’s bank activity statements.
- LINENAME - Train lines stopping at this location. Can contain up to 20 single character identifier. When more than one train line appears, it is usually intercepting train lines, in major stations where the passenger can transfer between any one of the lines.
- DIVISION - Represents the Line originally the station belonged to BMT, IRT, or IND. Each section of the system is assigned a unique line name, usually paired with its original operating company or division (Brooklyn–Manhattan Transit Corporation (BMT), Interborough Rapid Transit Company (IRT), and Independent Subway System (IND).
- DATE - Represents the date of the audit data.
- TIME - Represents the time of the audit data.
- DESC - Represents the “REGULAR” scheduled audit event (Normally occurs every 4 hours).
ENTRIES and EXITS are the cumulative values for a device.

