require 'base64'
task :dummy do
  sh %Q(curl -v "http://localhost:8153/go/api/admin/feature_toggles" -u "peter:#{ENV['SEC_VAR']}" -H "Confirm: true")
  #p "This is the encoded string : #{Base64.encode64(['admin', ENV['SEC_VAR']].join(':'))}"
end
