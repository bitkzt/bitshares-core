    scp programs/witness_node/systemd/witness_node.service kzdex-witness-fra:/etc/systemd/system/witness_node.service


    systemctl enable witness_node

    systemctl start witness_node
    systemctl restart witness_node
    systemctl stop witness_node
    systemctl status witness_node

После изменения скрипта

    systemctl daemon-reload

Логи

    journalctl -n 100 -f -u witness_node
