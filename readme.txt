=== Gravity Forms Approvals Add-On ===
Contributors: stevehenty
Tags: gravity forms, approvals, workflow
Requires at least: 5.2
Tested up to: 5.6.2
Stable tag: 1.2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add simple approval workflow processes to your Gravity Forms.

== Description ==

Gravity Forms Approvals is an add-on for the Gravity Forms plugin.

Gravity Forms Approvals adds simple approval processes to forms. This allows forms to be approved by an administrator upon submission. Approvals can be governed by conditional logic/routing to allow for a wide range of different workflow automations, such as:

* **Vacation request forms** for employees to complete company-wide. Form submissions must be approved or rejected by the employee’s department director. Pending approvals must be displayed in a personalized list for each director. The data from approved forms will be sent to a Google Spreadsheet.
* A system to handle the approval by the appropriate departmental director of all **incoming invoices**. e.g. Invoices over $9,999 must also have the approval of the Finance Director before the pricing data is sent to the ERP system.
* Allowing **user registration** on the front-end but ensuring that WordPress account signups can be approved by multiple admins before they are created and before the activation emails are sent to the users.

FEATURES

* Add new **Approval** functionality to your existing Gravity Forms forms.
* Use a simple approval process for Gravity Forms entries or configure complex **conditional logic** approvals dependent on individual form fields, drop-downs, checkboxes, radio buttons, and more.
* Send different notifications on **approval or rejection** events using conditional logic.
* Compatibility with a **wide range of Gravity Forms add-ons**.


If you use it and like it [please consider giving it a rating](http://wordpress.org/plugins/gravityformsapprovals/).

If this add-on doesn't quite meet your needs, or if you'd like an add-on that will grow with your business workflow processes you may want to check out [Gravity Flow](https://gravityflow.io). Gravity Flow supports multiple steps, process branching and loops, user input, approval policies, advanced conditional routing, timestamps, audit trail, comments, and it has a complete interface for users for pending tasks, submitting forms, and viewing the status of previously submitted forms.

If you’d like an add-on that will grow with your business workflow processes, check out [Gravity Flow](https://gravityflow.io). Endlessly scalable, secure, and easy-to-use, Gravity Flow is a powerful - and affordable - alternative to pay-per-user SaaS workflow tools.
Gravity Flow comes with an advanced Business automation feature set, including

- Multiple steps with over 50 different step types
- Process branching and review loops
- Complete frontend experience for workflow participants
- Entry editing in the frontend with User Input steps
- Approval policies
- Advanced conditional routing
- Timeline for each entry with detailed activity log
- Audit trails
- Integration triggers for third-party services
- Detailed reporting

It has a complete interface for users for pending tasks, submitting forms, and viewing the status of previously submitted forms.
Gravity Flow is trusted by customers from the City University of New York to Verizon.

= Requirements =

1. [Purchase and install Gravity Forms](http://www.stevenhenty.com/out/gravityforms) (Affiliate link)
2. WordPress 5.2+
3. The latest version of Gravity Forms.


= Support =
If you find any that needs fixing, or if you have any ideas for improvements, please get in touch:
http://www.stevenhenty.com/contact/


== Installation ==

1.  Download the zipped file.
1.  Extract and upload the contents of the folder to /wp-contents/plugins/ folder
1.  Go to the Plugin management page of WordPress admin section and enable the 'Gravity Forms Approval Add-On' plugin

== Frequently Asked Questions ==

= Which license of Gravity Forms do I need? =
Gravity Forms Approvals will work with any license of [Gravity Forms](http://www.stevenhenty.com/out/gravityforms). (Affiliate link)

= What capabilities (permissions) do users need to approve? =
Approvers need to be able to edit entries so they need the gravityforms_edit_entries capability

= How do I edit the capabilities for a user/role? =
You can use the [Members](https://wordpress.org/plugins/members/) plugin to edit the capabilities for each Role.

= I don't see the Approvals Form Settings tab =
Ensure your role is assigned the gravityformsapprovals_form_settings capability using the Members plugin.

= How do I set up notifications based on approval or rejection? =
Use the Conditional Logic setting on the notification to check for the approval status.

= Is Gravity Forms 2.5 supported? =
Yes!

== Screenshots ==

1. Entry approved
2. Approver configuration
3. Dashboard widget
4. Notification configuration
5. Pending approval
6. Approved

== ChangeLog ==

= 1.2.1 =
- Bumped tested up to and minimum versions.

= 1.2 =
- Fixed an issue with the Members plugin integration

= 1.1 =
- Bumped minimum version of Gravity Forms required to 2.4.
- Fixed an issue where approvers can't add notes.

= 1.0.1 =
- Added the gform_approvals_entry_rejected action which fires when an entry is rejected.
- Added the gform_approvals_entry_approved action which fires when an entry is approved.

= 1.0.0 =
- Bumping version

= 1.0-beta-5 =
- Fixed an issue where User Registration is skipped even when there are no approval feeds.
- Fixed an issue where the approval buttons appear even when conditional logic is not met.

= 1.0-beta-4 =
- Added the gravityformsapprovals_form_settings and gravityformsapprovals_uninstall capabilities for integration with the Members plugin.
- Updated some strings to be translatable.
- Fixed an issue with form settings tab which might not appear under certain conditions.

= 1.0-beta-3 =
Fixed an issue with the entry detail page where the approval buttons won't appear if the approver is changed in the feed settings.


= 1.0-beta-2 =
Adding support for translations

= 1.0-beta-1 =
Initial release

== Upgrade Notice ==

= 1.2 =
- Fixed an issue with the Members plugin integration

= 1.0-beta-3 =
Fixed an issue with the entry detail page where the approval buttons won't appear if the approver is changed in the feed settings.

= 1.0-beta-2 =
Adding support for translations

= 1.0-beta-1 =
Initial release