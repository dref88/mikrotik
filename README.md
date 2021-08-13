# Script to check Mikrotik BGP Session (applicable for nagios and others monitoring systems) 

## Requirements 📋
Perl

MikroTik::API perl library

    -> perl -MCPAN -e shell
    -> install MikroTik::API
    
Username and Password with access to the mikrotik router API 

## Install 🔧

1. Download script
2. Exec permissions

    -> chmod +x check_mk_bgp_session

## Usage

./check_mk_bgp_session -H <hostname> -U <mk_api_username> -P <mk_api_password> -N <bgp_peer_address> -s 1
