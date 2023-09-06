# Coding Challenge - Data & Platform team

Given the load balancer logs that you can find in this repo, 

- Find the percentage of requests that are redirected.
- Find the list of browsers used to access the application.
- Are requests from Google SEO being blocked?
- Is anyone trying to brute force the application?
- Find the number of requests per minute.

This is an open-book test so feel free to Google things, or ask questions!

The logs structure is as follows:
```
    'type'
    'timestamp'
    'elb'
    'client:port'
    'target:port'
    'request_processing_time'
    'target_processing_time'
    'response_processing_time'
    'elb_status_code'
    'target_status_code'
    'received_bytes'
    'sent_bytes'
    'request'
    'user_agent'
    'ssl_cipher'
    'ssl_protocol'
    'target_group_arn'
    'trace_id'
    'domain_name'
    'chosen_cert_arn'
    'matched_rule_priority'
    'request_creation_time'
    'actions_executed'
    'redirect_url'
    'error_reason'
    'target:port_list'
    'target_status_code_list'
    'classification'
    'classification_reason'
 ```
