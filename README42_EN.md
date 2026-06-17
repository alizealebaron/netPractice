*This project was created as part of the 42 curriculum by alebaron.*

## Description

**NetPractice** is a practical exercise designed to introduce the basics of computer networking. The main goal of this project is to configure small simulated networks and make them fully functional.

Through 10 progressive exercise levels, this project helps you understand and practice:
- **TCP/IP** addressing.
- Configuring **subnet masks**.
- Interconnecting devices using **routers** and **switches**.

## Instructions

### Launching the interface

The project runs on a simulated training interface accessible from a web browser. To launch it:

1. Download the compressed file attached to the project's page and extract it into a folder of your choice.
2. Run the local network script from your terminal:
```bash
   sh run.sh
```

Manual alternative: If the script fails because of browser security restrictions, you can manually start a Python server:
```bash
python3 -m http.server 49242
```

3. Then open http://localhost:49242 in your browser (where 49242 is the port you selected).

### Using the interface and validation

1. Enter your intranet login in the dedicated field to load your personal configuration (or use the "Evaluation" tab to generate a random network).
2. Complete the objectives shown at the top of the screen by modifying only the non-greyed fields in the diagram.
3. Use the [Check again] button to verify whether your network configuration is correct.
4. The logs displayed at the bottom of the page will help diagnose errors (missing gateway, invalid IP, etc.).

### Export and submission

1. Each time a level is successfully validated, you must click the [Get my config] button to download the level configuration file before moving on to the next level.
2. The final Git repository must contain exactly 10 exported configuration files (one file per validated level), placed directly at the root of your repository.

## Resources

## Documentation on network configuration

- [Static IP routing](https://fr.wikibooks.org/wiki/R%C3%A9seaux_TCP/IP/Le_routage_IP_statique)
- [TCP/IP Addressing](https://web.archive.org/web/20221003073118/https://sites.ualberta.ca/dept/chemeng/AIX-43/share/man/info/C/a_doc_lib/aixbman/commadmn/tcp_address.htm)
- [IPv4 addresses and subnet mask calculation](https://www.it-connect.fr/adresses-ipv4-et-le-calcul-des-masques-de-sous-reseaux/)
- [What is a network switch?](https://talice.com/actualites/quest-ce-quun-switch)
- [IP address](https://en.wikipedia.org/wiki/IP_address)

## Use of AI

- Proofreading and translation to English of the README
