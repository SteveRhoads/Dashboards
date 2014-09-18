Dashboards
==========

Various Dashboards and App Settings

Bad/No Estimates Query:
(((((((((((PlanEstimate != 0) 
AND (PlanEstimate != 0.5)) 
AND (PlanEstimate != 1)) 
AND (PlanEstimate != 2)) 
AND (PlanEstimate != 3)) 
AND (PlanEstimate != 5)) 
AND (PlanEstimate != 8)) 
AND (PlanEstimate != 13)) 
AND (PlanEstimate != 20)) 
AND (PlanEstimate != 40)) 
AND (PlanEstimate != 100))

Bad/No Estimates - Direct Grid Settings
(((((((((((PlanEstimate != 0) AND (PlanEstimate != 0.5)) AND (PlanEstimate != 1)) AND (PlanEstimate != 2)) AND (PlanEstimate != 3)) AND (PlanEstimate != 5)) AND (PlanEstimate != 8)) AND (PlanEstimate != 13)) AND (PlanEstimate != 20)) AND (PlanEstimate != 40)) AND (PlanEstimate != 100))

UserStoryDescriptionReady Query:
(((((((((Description = null)) 
OR (Description = "")) 
OR (Description !contains "As a")) 
OR (Description !contains "I want to")) 
OR (Description !contains "in Order to")) 
OR (Description !contains "How to Demo")) 
OR (Description !contains "Acceptance Criteria"))
OR  OR (Description !contains "PEPF"))

((((((((Description = null) 
OR (Description = "")) 
OR (Description !contains "As a")) 
OR (Description !contains "I want to")) 
OR (Description !contains "in Order to")) 
OR (Description !contains "How to Demo")) 
OR (Description !contains "Acceptance Criteria")) 
OR (Description !contains "PEPF"))


UserStoryDescriptionReady - Direct Grid Settings:
((((((((Description = null) OR (Description = "")) OR (Description !contains "As a")) OR (Description !contains "I want to")) OR (Description !contains "in Order to")) OR (Description !contains "How to Demo")) OR (Description !contains "Acceptance Criteria")) OR (Description !contains "PEPF"))
