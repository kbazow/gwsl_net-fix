# gwsl_net-fix
# Network port forwarding script - Fixes "Graphical ssh Connection" ssh and xserver over specified port
#
#  Network port forwarding script - GWSL & WSL2 with xserver - Fixes "Graphical ssh Connection" ssh and xserver over specified port
#
#    --Home - port 2222 Malrubius
#    --Work - Port 22 D7RS-WSKB-MCM, D7RS-WSKuB-MCM
#      --Home - for enable script, 'Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope CurrentUser' in Powershell --Home
#      --Work - for enable script, Run wit scripted signed with root CA
#      to delete existing rules and ports use 'delete' as flag/parameter
#          for show ports use 'list' as parameter.
#
#  Notes for later #
#  Windows Firewall Rules Will Differ From Work to Home
#        Revision 1.3 will have if/than implementation
#           Work will need Duo MFA and elevated rights
#           Home needs my elevation added
#
#
#
#  Written By:  Kurtis Bazow 1-22-22 revision 1.1
