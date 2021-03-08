# Aplikacja mobilna
    static page - mobile

## Sms link form
    * `tms_lead` module - form_sms_app_link ['mobile' => 'true']
         * `Data Layer`
        {
            "event": "GAevent",
            "eventCategory": "Aplikacja",
            "eventAction": "Numer",
            "eventLabel": md5(number)
        {

## Aplikacja mobilna TMS Brokers
    * Google play
        !empty(($trackerUrl = \Tms\Helpers\Ws\AdjustHelper::instance()->getSiteTrackerUrl())) ? $trackerUrl : 'https://bprw.adj.st/?adjust_t=moiq3fk'
    * App store
        !empty(($trackerUrl = \Tms\Helpers\Ws\AdjustHelper::instance()->getSiteTrackerUrl())) ? $trackerUrl : 'https://bprw.adj.st/?adjust_t=moiq3fk'