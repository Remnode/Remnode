

<p align="center">
  <img src="media/image.jpg" alt="Remnode logo" width="112" />
</p>

<h1 align="center">Remnode</h1>

<p align="center">
  <strong>A temporary Windows desktop, ready when you need it.</strong>
</p>

<p align="center">
  On-demand sessions · AnyDesk access · Optional RDP
</p>

---

**Remnode** provides a temporary Windows remote desktop powered by GitHub Actions. Start a session on demand, connect through AnyDesk, and use the optional RDP connection when needed.

## Preview

https://github.com/user-attachments/assets/7f7895c7-4c6a-41a8-ad27-a1a936fee363

## Features

| Feature | Description |
|---|---|
| **On-demand sessions** | Start a Windows session manually through GitHub Actions. |
| **Windows environment** | Runs on GitHub's `windows-latest` hosted runner. |
| **AnyDesk access** | Remotely access the desktop using AnyDesk unattended access. |
| **Optional RDP** | Alternative remote access through a Bore tunnel. |
| **Secret-managed password** | AnyDesk password is supplied through the `REMNODE_ANYDESK_PASSWORD` GitHub Actions secret. |
| **Extended session window** | Workflow job timeout is configured for up to 360 minutes. |

## Session & data

> [!IMPORTANT]
> Remnode uses a temporary GitHub-hosted runner. The virtual machine is decommissioned when the job finishes. Files, applications, and other data stored only on that machine should be considered temporary.

## Security

- Keep `REMNODE_ANYDESK_PASSWORD` in GitHub Actions secrets. Never commit it to the repository or print it in workflow logs.
- The AnyDesk password does not protect the RDP connection.
- When RDP is enabled, protect the Windows account and restrict access to the Bore tunnel endpoint. Treat the endpoint as sensitive.

---

<p align="center">
  <strong>Remnode</strong>
  <br />
  <sub>Temporary access. Your workspace, on demand.</sub>
</p>

