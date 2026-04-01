cat > app.json << 'EOF'
{
  "id": "c3d4e5f6-7890-abcd-ef12-345678901234",
  "name": "BLM Lursoft Integration",
  "publisher": "Belam-Riga",
  "version": "1.0.0.0",
  "platform": "24.0.0.0",
  "application": "24.0.0.0",
  "idRanges": [{ "from": 50100, "to": 50199 }],
  "dependencies": [
    {
      "id": "a7b8c9d0-1234-5678-abcd-ef0123456789",
      "name": "BLM Registers",
      "publisher": "Belam-Riga",
      "version": "1.8.0.2"
    }
  ],
  "runtime": "12.0",
  "features": ["NoImplicitWith"]
}
EOF

    
