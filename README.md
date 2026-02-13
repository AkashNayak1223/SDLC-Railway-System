Case Study: Railway Reservation Management System

The Railway Reservation Management System is a large-scale software system that allows:

- Online ticket booking  
- Train search and seat availability  
- Ticket cancellation and refund  
- PNR generation  
- Administrative control of schedules and fares  

This system involves multiple stakeholders including passengers, administrators, railway authorities, and payment gateway providers.

 SDLC Models Compared

1. Waterfall Model
A sequential development approach where each phase must be completed before the next begins.  
Suitable when requirements are fixed and clearly defined.

2. Incremental Development Model
The system is developed in multiple increments.  
Each increment delivers functional components of the system.  
Suitable when requirements evolve gradually.

3. Spiral Model
Risk-driven model combining iterative development and risk analysis.  
Suitable for large-scale and high-risk systems.


* Requirements Engineering Process

Two versions of requirements documents are included:

Initial requirements
- Initial draft
- Basic functional and non-functional requirements
- Limited security and performance specifications

Revised requirements
- Revised after validation
- Added OTP verification
- Added PNR generation
- Included waitlist and RAC logic
- Improved performance benchmarks
- Added scalability and security enhancements

This demonstrates requirement evolution and change management.


Branching and Merging Strategy

The following Git strategy was followed:

- `main` branch → Final stable submission
- `requirements-draft` branch → Initial version (v1)
- `requirements-revision` branch → Updated version (v2)
- `report-development` branch → Report writing and comparison sections

Workflow:

1. Created requirements_v1 in requirements-draft branch.
2. Merged into main after review.
3. Created requirements_v2 in requirements-revision branch.
4. Compared changes and updated documentation.
5. Final report merged into main branch.

This strategy ensures:
- Version control
- Traceability
- Clear change tracking
- Structured development process

Risk and Change Management Considerations

Key risks identified:

- High user traffic during peak booking periods  
- Payment gateway failure  
- Data security threats  
- Policy changes in railway regulations  

The Spiral Model was found to be most suitable for handling such risks.

Conclusion

After comparison:

- Waterfall is suitable for stable requirements.
- Incremental model is suitable for phased delivery.
- Spiral model is most appropriate for large-scale, high-risk systems like Railway Reservation Management System due to its risk-driven approach.



Author

Name: Akash Narasimha Nayak  
Course:IS3332-1  
Department: Information Science & Engineering  
Institution: NMAMIT  
Academic Year: 2025-2026
