# PyCoin
Purpose: To watch the btc (and ltc) market(s), collect data, and eventually make an algorithm-based bot to make trades wihtin the markets for financial gain. Market is GDAX.  
System Arch: Module-based, client-server based with a central handler (#1).  
Language: Python, until something better comes along. 

### Module #1
Module English Name: Trading Dashboard  
SW Name: TradingDashboard  
Purpose: Aggregate realtime data for display. This is the UI/GUI/HMI  
Notes: Data displayed could be historical queries, bot metrics, bot algo's, etc  

### Module #2
Module English Name: Data Collector  
SW Name: DataMgr  
Purpose: Collects and manages historical data.  
Notes: Will need to hash out how to store so that it is efficient and usable.

### Module #3
Module English Name: API Manager  
SW Name: APIMgr  
Purpose: Makes ALL API calls to the exchange  
Notes:Used by dash and bots

### Module #4
Module English Name: Bot Manager  
SW Name: BotMgr  
Purpose: Keep's track of which bot's are enabled/running and monitor's threading  
Notes:Last of the first three modules to implement. Will need some thought.
