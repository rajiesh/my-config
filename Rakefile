task :dummy do
  #sh "curl -v 'http://localhost:8153/go/api/admin/feature_toggles' -u 'пароль:#{ENV["SEC_VAR"]}' -H 'Confirm: true'"
  Base64.encode64(['admin', ENV['SEC_VAR']].join(':'))
end
