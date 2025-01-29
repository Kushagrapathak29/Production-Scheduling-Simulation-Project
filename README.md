To create a shift-wise production simulation, the first step is to load and examine the production data. The data is extracted from an Excel file containing details such as order quantity, processing sequence, machine assignments, process times, changeover times, and batch sizes. Once the data is loaded, it is cleaned by removing missing values and ensuring all relevant columns are correctly formatted as numerical values for accurate calculations.

After cleaning the data, it is grouped by SKU and sequence to establish the correct flow of production. This grouping helps identify how components move through different machines, ensuring that each component is processed in the right order. Next, a simulation function is created to calculate the total time required for each component’s processing. This function considers factors such as the time required to process each part, the number of batches, and changeover times between machine transitions. The function then estimates the total production time in hours and calculates the number of shifts and days required for production based on a defined shift schedule.

Once the simulation is completed, the results are analyzed to identify bottleneck machines. Machines that require the highest processing times are flagged as potential constraints in the production line. The longest lead time is also determined by finding the maximum number of days required to complete a component’s processing. This insight is crucial in optimizing the production schedule and identifying areas where efficiency improvements can be made.

A machine utilization matrix is then constructed to distribute processing hours across different shifts. This matrix maps machines against shifts, showing how much time each machine is used in a particular shift. By analyzing this matrix, inefficiencies can be identified, and workload can be distributed more evenly across available shifts.

Lastly, a machine loading plan is generated to determine the total load each machine bears over the entire production period. This plan summarizes the total working hours for each machine, providing a comprehensive view of machine utilization. The results from the simulation, bottleneck identification, machine utilization matrix, and machine loading plan together provide a detailed production analysis that can help optimize the manufacturing process.





