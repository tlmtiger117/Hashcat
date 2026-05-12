# 12/05/26

- Sintaxe: hashcat -m <tipo_hash> -a <modo_ataque> <arquivo_hashes> <wordlist>

- Flags comuns:
  
   - -m -> define o tipo de hash
   - -a -> define o modo de ataque
   - -o -> salva as senhas encontradas
   - -r -> aplica regras/mutações na wordlist
   - -w -> ajusta performance/workload
   - -O -> ativa otimizações
   - -D -> escolhe CPU ou GPU
   - --force -> força execução ignorando avisos
   - --status -> mostra status em tempo real
   - --status-timer -> intervalo do status
   - --show -> mostra hashes quebrados
   - --remove -> remove hashes já quebrados
   - --username -> ignora usernames no arquivo
   - --session -> cria nome de sessão
   - --restore -> restaura sessão pausada

