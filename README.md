s.Week 1 (new deadline: 16.03.2025- Sunday): 

Frontend: 
- Finish Landing page (what we have in the Figma UI/Ux exmaple). Components:
   - Header
   - Main Landing Page
   - Services Menu (Bubbles)
   - Register as a service provider (freelancer)
   - Download the app Section
   - Support
   - Reviews
   - Footer

**Backend:**
**- User Management**
- user model
- build password system
- build auth system based on jwt
- include OAUTH for creating Bearer Tokens
- API Routes (/auth/register, /auth/login, /auth/me)
- Error Handling for API Routes

**T01 - Test API Routes and the errors**

TC01 - New account 

TC02 - Login with right credentials

TC03 - Register existing e-mail throws validation error

TC04 - Login with wrong credentials throws validation error

TC05 - Login with wrong format e-mail throws format error


**MP01 - Dummy Testing FrontEnd**
- build the testing front-end

**F02 - User Roles**
- build & define user rules and the role model
- RBAC (role based access contorl)
- API Routes for assigning roles, removing roles, checking roles, showing all users of a specific role

**F03 - Services & Offers**
- create Service model
- API Routes for Services
- create Offer model
- API Routes for offers
- Service 1:many Offers relationship in DB
- PROFESSIONAL (PRUR) creates offers
- CUSTOMER (CTUR) sees offers
- API Route for offer management

**F04 - Bookings (for Sprint 2)**
- Booking Model
- API Routes for Bookings
- CTUR books, PRUR accepts
- Booking statuses: Pending, Accepted/Refused, Completed
- Booking notifications (sms and e-mail) for status updates
- PRUR Manages their orders and move through statuses

**MP02 - Mailing System (for Sprint 2)**
- e-mail notifications
- websocket for real time updates

Backlog:
- Reviews System
- Rating System + Tier system
- Payments & Currency
- Admin Dashboard
- Language selector
- Signup as a freelanecr
- Profile page for CTUR, PRUR
- Chat system
- Search bar pe baza de recomandari/matching
  
Infra: 
 - File Structure
 - Maybe main.bicep file + workflows, but not really needed for now
