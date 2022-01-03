SELECT Region_Encoder,SUM(Total) AS Total FROM Exercise
GROUP BY Region_Encoder;

SELECT `Data source_Enncoder`,count(`Data source_Enncoder`) AS Total FROM Exercise
GROUP BY `Data source_Enncoder`;

SELECT `Time period`,count(`Time period`) AS Total FROM Exercise
GROUP BY `Time period`;
