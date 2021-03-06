List of available actions
=========================

Yii2-user includes a lot of actions, which you can access by creating URLs for
them. Here is the table of available actions which contains route and short
description of each action. You can create URLs for them using special Yii
helper ``\yii\helpers\Url::to()``.

=================================== ========================================================
Route                               Description
=================================== ========================================================
**/user/registration/register**     Displays registration form
**/user/registration/resend**       Displays resend form
**/user/registration/confirm**      Confirms a user (requires *id* and *token* query params)
**/user/security/login**            Displays login form
**/user/security/logout**           Logs the user out (available only via POST method)
**/user/recovery/request**          Displays recovery request form
**/user/recovery/reset**            Displays password reset form (requires *id* and *token* query params)
**/user/settings/profile**          Displays profile settings form
**/user/settings/email**            Displays email settings form
**/user/settings/password**         Displays password settings form
**/user/profile/show**              Displays user's profile (requires *id* query param)
**/user/admin/index**               Displays user management interface
=================================== ========================================================
