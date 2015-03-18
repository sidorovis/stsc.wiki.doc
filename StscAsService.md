Stsc As Service
---------------

Stsc as service is a sub-project to enable different possibility to observe and start simulation process from the web.

#### Components
Components for webStsc are:

##### Data Downloading Module

 * current state for all downloaders (for example Yahoo, Feedzilla; is it in process / last 10 executions average run time and etc.).

##### Data Storage Module | TBD

 * stock downloaded datafeed statistics and summary information by stock (how many days do stock have, is it liquid, is it valid, additional information like name, type (eod) and etc.);
 * news downloaded datafeed statistics and summary information by category/subcategory/author (how many days, how many information rows);
 * existing algorithms (small description, start lines, examples for executions, some comments and advices how to use algorithm);

##### Simulated Strategies Viewer Module | TBD

 * simulated strategies (by time-stamp / personal string identificator);
 * settings / statistics information per each strategy;
 * ! time to execute (description for strategy generating process: is it grid or genetic, compare function, interval for one simulation / population simulation;

##### Calculation Grid Module | TBD

 * description of calculation grid: amount of nodes;
 * current state: (how many nodes we have on 'cluster');
 * ! possibility to add new calculation node to the network (for example from amazon, or some personal PC's by IP's);

##### Simulation Starter Module | TBD

 * settings editor, compare function editor and etc;
 * ! simulation process planning (how many resources from calculation nodes we should use a etc.)

