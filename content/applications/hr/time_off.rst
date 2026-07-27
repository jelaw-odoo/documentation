:show-content:

========
Time off
========

Odoo's **Time Off** application serves as a centralized hub for all time-off-related information.
This application manages requests, balances, allocations, approvals, and reports.

Users can :doc:`request time off <../hr/time_off/request_time_off>`, and see an overview of their
requests and time off balances. Managers can :doc:`allocate time off <time_off/allocations>` to
individuals, teams, or the whole company, and :ref:`approve time off requests
<time_off/manage-time-off>`.

Detailed :doc:`reports <time_off/reporting>` can be run to see how much time off (and what kinds of
time off) are being used, :doc:`accrual plans <time_off/accrual_plans>` can be created, and
:doc:`public holidays <time_off/public_holidays>` can be set.

.. note::
   Be advised, only users with specific access rights can see all aspects of the **Time Off** app.

   All users can access the *My Time Off* and *Overview* sections of the **Time Off** app. All other
   sections require specific access rights.

   To better understand how access rights affect the **Time Off** app, refer to the
   :doc:`employees/new_employee` document, specifically the section about configuring the *Work
   Information* tab.

.. seealso::
   :doc:`../general/users/access_rights`

Configuration
=============

In order to allocate time off to employees, and for employees to request and use their time off, the
various :doc:`time off types must be configured <time_off/time_off_types>` first, then
:doc:`allocated <time_off/allocations>` to employees (if allocation is required).

Overview
========

To view a color-coded schedule of the user's time off, and/or of the team managed by them, navigate
to :menuselection:`Time Off app --> Overview`. This presents a calendar with the default filter of
`My Team`, in a quarterly (three month) view.

To change the time period displayed, click on the :icon:`fa-calendar` :guilabel:`(time period)`
button to reveal a drop-down menu. Then, select either :guilabel:`Today`, :guilabel:`This week`,
:guilabel:`This month`, :guilabel:`This year`, or a custom time period, to present the calendar in
that corresponding view.

To navigate forward or backward in time, in the selected increment (:guilabel:`Month`,
:guilabel:`Week`, etc.), click the :icon:`oi-arrow-left` :guilabel:`(left arrow)` or
:icon:`oi-arrow-right` :guilabel:`(right arrow)` buttons to move either forward or backward in that
specified amount of time. For example, if :guilabel:`Month` is selected, the arrows adjust the view
by one month.

To return to a view containing the current day, click the :icon:`fa-crosshairs` :guilabel:`(Focus
Today)` button at any time.

Team members are listed alphabetically on individual lines, and their requested time off, regardless
of the status (*validated* or *to approve*), is visible on the calendar.

Each employee is color-coded. The employee's color is selected at random, and does *not* correspond
to the type of time off they requested.

The status of the time off is represented by the color detail of the request, either appearing solid
(*validated*) or striped (*to approve*).

The number of days or hours requested is written on the request (if there is enough space).

At the bottom of the calendar, in the :guilabel:`Total` line, a bar graph shows how many people are
projected to be out on any given day. The number on each individual bar represents the number of
employees out for those highlighted days.

Click on a time off entry to view the details for the specific time off entry. The total number of
hours or days are listed, along with the start and end time of the time off. To view the details of
the time off request in a modal, click the :guilabel:`View` button.

.. image:: time_off/overview.png
   :alt: Overview of the user's team, with time off requests shown.

.. seealso::
   - :doc:`time_off/time_off_types`
   - :doc:`time_off/accrual_plans`
   - :doc:`time_off/public_holidays`
   - :doc:`time_off/mandatory_days`
   - :doc:`time_off/allocations`
   - :doc:`time_off/request_time_off`
   - :doc:`time_off/my_time`
   - :doc:`time_off/management`
   - :doc:`time_off/reporting`

.. toctree::
   :titlesonly:

   time_off/time_off_types
   time_off/accrual_plans
   time_off/public_holidays
   time_off/mandatory_days
   time_off/allocations
   time_off/request_time_off
   time_off/my_time
   time_off/management
   time_off/reporting
