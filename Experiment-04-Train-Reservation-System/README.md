# Experiment 04: Online Train Reservation System

## Aim
To design and develop an Online Railway Reservation System that enables passengers to query train schedules, inspect via-stop details and seat availability by class, execute bookings with automated 10-digit PNR generation, verify PNR status (Confirmed, RAC, Waiting List), and process cancellations using standardized refund rules.

---

## Problem Statement
The online train reservation system allows users to search for trains by route, date, and time, and view available seats and classes.

### Core System Features
1. **Passenger Login & Journey Details**: Input date of journey, passenger names/details, origin, destination, and class type (1A, 2A, 3A, SL).
2. **Train & Via-Details**: Display available train list, seat availability, and via-stops.
3. **Payment & PNR Generation**: Support online and offline payment modes; generate a 10-digit PNR number upon fare payment, and forward payment details to the system Admin.
4. **PNR Status Verification**: Check real-time status (Confirmed, RAC, Waiting List).
5. **Admin Management**: Maintain train details, fare details (by zone, class, date-wise), PNR records, and schedule dates.
6. **Refund Rules & Cancellation**: Automatic calculation of refundable percentage based on reservation date and journey proximity. Passenger cancels ticket via PNR, Admin approves and returns the refundable amount.

---

## Output Screenshot
Below is the captured output of the Online Train Reservation System:

![Experiment 04 Output Screenshot](screenshot.png)

---

## Conclusion
The Train Reservation System successfully satisfies all 6 requirements including via-route inspection, 10-digit PNR assignment, real-time availability by class, and dynamic refund rule execution.


## 5. Source Code Execution Screenshot
A capture of the source code implementation (`index.html`) executed for this experiment:
![Source Code Screenshot](code_screenshot.png)

## 6. Execution Output Verification
The execution output and verification details are recorded directly inside the source code comments of `index.html` and visually confirmed in `screenshot.png`.
