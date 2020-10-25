## About me

I spent the best part of the last decade building data solutions.

I have worked on starting from the lowest end of the data spectrum of analysing data in spreadsheets to building highly scalable data platforms that feed machine learning models that drive business decisions.

I have done well for myself and for the organizations that I have worked for.

Over these years, I have picked up quite a lot of skills as part of my job and out of plain curiosity. 

Many of which came really handy at making short work of seemingly complex tasks. 

I am a very hands-on person. 

I continue to learn and I am passionate about my education and gaining expertise.

I have worn a lot of hats over the years. 
Starting with building web solutions,  
Designed and built database backends, datawarehouses
Implemented ETL solutions using both off-the-shelf tools and programming libraries
Re-did most of the above tasks on cloud platforms
Built and deployed web services 
Designed and developed dashboards
I am comfortable with containerized solutions and orchestrating them

I like to think of myself as a problem solver at the core and someone who likes to roll out solutions fast and improve them iteratively.

In my most recent role at CIBC, I did just that.
I did a lot of data plumbing to get the data in the right place, shape and form to be reported.

I designed and built their data visualization dashboards for consumption by the senior management.

Now because it's a bank, I hope you understand that there are challenges in tools and technology adoptions and lot of a times getting work done means having to stitch together solutions that may involve legacy technology stacks and adhoc scripts.
CIBC was no different. 

I did face a lot of challenges. But I managed to overcome them and build solutions to transform the reporting in the department where I was contracted. 

The technology stack used were a mix of `Python`, `SQL`, `NodeJS`, `Tableau`, `.Net Core 3.1` and some plain old `VBA`.

Prior to CIBC, I was part of the Advanced Analytics team at IHS Markit.
At IHS, I built data engineering pipelines involving a stack of tools like AWS S3, Redshift, Athena, Airflow, Python, Pandas, Apache Spark and a ton of scripts.

I also developed analytical dashboards showcasing the results from the machine learning models. 

I am currently taking some time off to learn some new skills and sharpen my axe.



------------------------------------------------------------------------------------------------
Now before you judge me for the VBA part, I must say this. 
A problem had to solved and it had to be done fast. And I got it done.
And that's what I am all about. Solving problems and getting things done.




If you client is looking for someone who has designed and implemented data warehouses, built, maintained and troubleshooted data engineering pipelines, developed and deployed dashboards using off-the-shelf tools like Tableau, TIBCO Spotfire, PowerBI or custom built solutions in Leaflet.js, D3, plotly, NodeJS then I am the man for that job.

Aside from the successes that I've had, I have personally faced most of the pain points, gotchas and failures in data development, engineering and visualization so that my clients wouldn't have to.  I guess that's the most important selling point that I bring to the table.

Attached herewith is my updated resume. There's only so much I can fit in 2 pages of what I have experienced and built over more than a decade.
I will be happy to get on a call/meeting to illustrate how I can add value and solve the business problem at hand.



I spent a lot of time migrating ETL jobs from a cron job driven model to a workflow orchestrator. 


Cron -> time-based scheduler

We chose Apache Airflow because of all the good things we read about it and also because it solves most of the pain points we were experiencing. 
Like automatically restarting failed tasks, controlling concurrency and dependencies.
But mostly because of the dependencies involved in complex workflows we couldn't predict when the upstream task would complete.
It got even more complicated when we're waiting for input from a third-party module.

I have gone through all the typical struggles one would face from moving the cron tasks on EC2 to a Spark cluster with Airflow orchestrating the Pyspark jobs.

I've had a fair share of experience migrating data analysis queries in hive running on hadoop to spark for faster data processing.

Typical configuration: Airflow configured on a EC2 instance which orchestrates all the calls.
Pulling data from various sources into S3
From S3 into Redshift
Submitting spark jobs to process data from hdfs and save as parquet on S3.


