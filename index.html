import React, { useState, useMemo } from "react";
import {
  LayoutDashboard, UtensilsCrossed, LayoutGrid, ArrowLeft, Search, Plus, Minus,
  ShoppingCart, Printer, Save, CheckCircle2, Wallet, CreditCard, MoreHorizontal,
  Calendar, Users2, Receipt, History, PlusCircle, Menu as MenuIcon, ChevronDown,
  ChefHat, Wifi, Signal, BatteryFull
} from "lucide-react";

/* ---------------------------------- THEME ---------------------------------- */
const C = {
  maroon: "#A31E24",
  maroonDark: "#7C1418",
  maroonSoft: "#FDECEC",
  maroonSoft2: "#FBDCDC",
  cream: "#FFFBF6",
  paper: "#FFFFFF",
  gold: "#8B6A3F",
  ink: "#2A1414",
  inkSoft: "#7A6666",
  line: "#F1E4E4",
};

/* ---------------------------------- DATA ---------------------------------- */
const CATEGORIES = ["Breakfast", "Meals", "Chapati Bhaji", "Tea & Coffee"];

const MENU = {
  Breakfast: [
    { id: "pohe", name: "Pohe", price: 30, emoji: "🍚" },
    { id: "upma", name: "Upma", price: 30, emoji: "🥣" },
    { id: "sheera", name: "Sheera", price: 40, emoji: "🍮" },
    { id: "khichdi", name: "Khichdi", price: 50, emoji: "🍲" },
    { id: "misalpav", name: "Misal Pav", price: 90, emoji: "🌶️" },
    { id: "vadasambar", name: "Vada Sambar", price: 55, priceNote: "₹55 / 70", emoji: "🍩" },
    { id: "idlisambar", name: "Idli Sambar", price: 30, priceNote: "₹30 / 50", emoji: "⚪" },
  ],
  Meals: [
    { id: "vegthali", name: "Veg Thali", price: 120, emoji: "🍽️" },
    { id: "dalrice", name: "Dal Rice", price: 80, emoji: "🍚" },
    { id: "vegpulao", name: "Veg Pulao", price: 90, emoji: "🍛" },
    { id: "paneermasala", name: "Paneer Masala", price: 140, emoji: "🧡" },
    { id: "curdrice", name: "Curd Rice", price: 70, emoji: "🥣" },
  ],
  "Chapati Bhaji": [
    { id: "chapati", name: "Chapati (2 pc)", price: 20, emoji: "🫓" },
    { id: "bhajipav", name: "Bhaji Pav", price: 40, emoji: "🍔" },
    { id: "aloosabzi", name: "Aloo Sabzi", price: 50, emoji: "🥔" },
    { id: "paneerbhurji", name: "Paneer Bhurji", price: 90, emoji: "🍳" },
    { id: "dalfry", name: "Dal Fry", price: 60, emoji: "🍲" },
  ],
  "Tea & Coffee": [
    { id: "tea", name: "Tea", price: 15, emoji: "☕" },
    { id: "coffee", name: "Coffee", price: 20, emoji: "☕" },
    { id: "masalatea", name: "Masala Tea", price: 20, emoji: "☕" },
    { id: "blacktea", name: "Black Tea", price: 10, emoji: "🍵" },
    { id: "lemontea", name: "Lemon Tea", price: 15, emoji: "🍋" },
  ],
};

const ALL_ITEMS = Object.values(MENU).flat().reduce((acc, i) => (acc[i.id] = i, acc), {});
const TABLES = [1, 2, 3, 4, 5];

/* ------------------------------- SMALL PIECES ------------------------------- */
function StatusBar() {
  return (
    <div className="flex items-center justify-between px-5 pt-3 pb-1 text-white text-[13px] font-medium">
      <span>9:41</span>
      <div className="flex items-center gap-1">
        <Signal size={13} /> <Wifi size={13} /> <BatteryFull size={15} />
      </div>
    </div>
  );
}

function Header({ title, onBack, right, menu }) {
  return (
    <div className="px-4 pb-4 pt-1 flex items-center gap-3 text-white">
      {onBack ? (
        <button onClick={onBack} className="p-1 -ml-1 active:opacity-60">
          <ArrowLeft size={22} />
        </button>
      ) : menu ? (
        <button className="p-1 -ml-1 active:opacity-60">
          <MenuIcon size={22} />
        </button>
      ) : (
        <span className="w-6" />
      )}
      <h1 className="text-[17px] font-semibold tracking-tight flex-1">{title}</h1>
      {right}
    </div>
  );
}

function Rupee({ n }) {
  return <>₹{Number(n).toLocaleString("en-IN")}</>;
}

function Stepper({ qty, onDec, onInc }) {
  if (qty > 0) {
    return (
      <div className="flex items-center rounded-full overflow-hidden" style={{ border: `1.5px solid ${C.maroon}` }}>
        <button onClick={onDec} className="w-7 h-7 flex items-center justify-center active:opacity-60" style={{ color: C.maroon }}>
          <Minus size={14} />
        </button>
        <span className="w-6 text-center text-[13px] font-semibold" style={{ color: C.maroon }}>{qty}</span>
        <button onClick={onInc} className="w-7 h-7 flex items-center justify-center text-white active:opacity-80" style={{ background: C.maroon }}>
          <Plus size={14} />
        </button>
      </div>
    );
  }
  return (
    <button
      onClick={onInc}
      className="w-8 h-8 rounded-full flex items-center justify-center text-white active:scale-95 transition-transform"
      style={{ background: C.maroon }}
    >
      <Plus size={16} />
    </button>
  );
}

/* --------------------------------- SCREENS ---------------------------------- */

function HomeScreen({ go }) {
  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: `linear-gradient(180deg, ${C.maroon}, ${C.maroonDark})` }}>
        <StatusBar />
        <div className="flex flex-col items-center pt-4 pb-7 px-6">
          <div className="w-20 h-20 rounded-full bg-white flex items-center justify-center shadow-md">
            <ChefHat size={38} color={C.maroon} />
          </div>
          <p className="mt-3 text-[11px] tracking-wide text-white/80">होटेल</p>
          <h1 className="text-2xl font-bold text-white leading-none">GANESH</h1>
          <p className="text-white/85 text-[11px] mt-1">प्युअर व्हेज &nbsp;•&nbsp; PURE VEG</p>
          <p className="text-white/70 text-[11px] mt-2 tracking-wide">AAVAD TUMCHI, CHAAV AAMCHI</p>
        </div>
      </div>

      <div className="flex-1 px-5 pt-6 flex flex-col gap-3.5">
        <NavCard icon={<LayoutDashboard size={20} />} label="Dashboard" onClick={() => go("dashboard")} />
        <NavCard icon={<LayoutGrid size={20} />} label="Tables" onClick={() => go("tables")} />
        <NavCard icon={<UtensilsCrossed size={20} />} label="Menu" onClick={() => go("tables")} />

        <div className="mt-auto mb-6 text-center">
          <p className="italic text-[15px]" style={{ fontFamily: "'Playfair Display', serif", color: C.gold }}>
            Good Food Brings People Together
          </p>
          <p className="text-[10px] mt-2" style={{ color: C.inkSoft }}>v1.0</p>
        </div>
      </div>
    </div>
  );
}

function NavCard({ icon, label, onClick }) {
  return (
    <button
      onClick={onClick}
      className="w-full flex items-center gap-3 px-5 py-4 rounded-2xl text-white active:scale-[0.98] transition-transform shadow-sm"
      style={{ background: C.maroon }}
    >
      {icon}
      <span className="text-[15px] font-medium flex-1 text-left">{label}</span>
      <ArrowLeft size={16} className="rotate-180 opacity-80" />
    </button>
  );
}

function DashboardScreen({ go, savedBills, cart }) {
  const totalSales = savedBills.reduce((s, b) => s + b.total, 0);
  const totalBills = savedBills.length;
  const activeTables = TABLES.filter((t) => Object.values(cart[t] || {}).some((q) => q > 0)).length;
  const byMethod = { Cash: 0, UPI: 0, Other: 0 };
  savedBills.forEach((b) => (byMethod[b.payment] = (byMethod[b.payment] || 0) + b.total));

  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: C.maroon }}>
        <StatusBar />
        <Header title="Dashboard" onBack={() => go("home")} />
      </div>

      <div className="flex-1 overflow-y-auto px-4 pt-4 pb-6">
        <div className="flex items-center gap-2 rounded-xl px-3.5 py-2.5 mb-4" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
          <Calendar size={15} color={C.maroon} />
          <span className="text-[13px] font-medium" style={{ color: C.ink }}>Tue, 15 Sep 2026</span>
          <ChevronDown size={14} className="ml-auto" color={C.inkSoft} />
        </div>

        <div className="grid grid-cols-2 gap-3 mb-3">
          <StatCard icon={<Rupee n="" />} label="Total Sales" value={<Rupee n={totalSales} />} />
          <StatCard icon={<Receipt size={16} />} label="Total Bills" value={totalBills} />
        </div>
        <div className="grid grid-cols-2 gap-3 mb-5">
          <StatCard icon={<Users2 size={16} />} label="Active Tables" value={`${activeTables} / 5`} />
          <StatCard icon={<LayoutGrid size={16} />} label="Available Tables" value={`${5 - activeTables} / 5`} />
        </div>

        <p className="text-[13px] font-semibold mb-2" style={{ color: C.maroon }}>Today's Sales <span className="font-normal" style={{ color: C.inkSoft }}>(Payment Method)</span></p>
        <div className="rounded-xl mb-5 overflow-hidden" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
          <PayRow icon={<Wallet size={15} />} label="Cash" value={byMethod.Cash} />
          <PayRow icon={<CreditCard size={15} />} label="UPI" value={byMethod.UPI} />
          <PayRow icon={<MoreHorizontal size={15} />} label="Other" value={byMethod.Other} last />
        </div>

        <p className="text-[13px] font-semibold mb-2" style={{ color: C.maroon }}>Quick Actions</p>
        <div className="grid grid-cols-2 gap-3">
          <QuickBtn icon={<Receipt size={15} />} label="View Today's Bills" />
          <QuickBtn icon={<History size={15} />} label="View Reports" />
        </div>
      </div>
    </div>
  );
}

function StatCard({ icon, label, value }) {
  return (
    <div className="rounded-xl px-4 py-3.5 flex flex-col gap-2" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
      <div className="w-8 h-8 rounded-full flex items-center justify-center" style={{ background: C.maroonSoft, color: C.maroon }}>{icon}</div>
      <div className="text-lg font-bold" style={{ color: C.ink }}>{value}</div>
      <div className="text-[11px]" style={{ color: C.inkSoft }}>{label}</div>
    </div>
  );
}

function PayRow({ icon, label, value, last }) {
  return (
    <div className="flex items-center gap-2.5 px-4 py-3" style={{ borderBottom: last ? "none" : `1px solid ${C.line}` }}>
      <span style={{ color: C.maroon }}>{icon}</span>
      <span className="text-[13px] flex-1" style={{ color: C.ink }}>{label}</span>
      <span className="text-[13px] font-semibold" style={{ color: C.ink }}><Rupee n={value} /></span>
    </div>
  );
}

function QuickBtn({ icon, label }) {
  return (
    <button className="flex items-center gap-2 px-3.5 py-3 rounded-xl text-[12.5px] font-medium active:scale-[0.98] transition-transform" style={{ background: C.paper, border: `1px solid ${C.line}`, color: C.ink }}>
      <span style={{ color: C.maroon }}>{icon}</span>{label}
      <ArrowLeft size={13} className="rotate-180 ml-auto opacity-50" />
    </button>
  );
}

function TablesScreen({ go, cart, selectTable }) {
  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: C.maroon }}>
        <StatusBar />
        <Header title="Tables" onBack={() => go("home")} />
      </div>
      <div className="flex-1 overflow-y-auto px-4 pt-4 pb-4">
        <div className="grid grid-cols-2 gap-3.5">
          {TABLES.map((t) => {
            const active = Object.values(cart[t] || {}).some((q) => q > 0);
            return (
              <button
                key={t}
                onClick={() => { selectTable(t); go("menu"); }}
                className="aspect-square rounded-2xl flex flex-col items-center justify-center gap-2 active:scale-[0.97] transition-transform"
                style={{
                  background: active ? C.maroonSoft2 : C.paper,
                  border: `1.5px solid ${active ? C.maroon : C.line}`,
                }}
              >
                <div className="text-2xl" style={{ color: C.maroon }}>🪑</div>
                <span className="text-[13px] font-semibold" style={{ color: C.ink }}>Table</span>
                <span className="text-lg font-bold" style={{ color: C.maroon }}>{t}</span>
              </button>
            );
          })}
        </div>
        <div className="mt-4 flex items-start gap-2.5 rounded-xl px-3.5 py-3" style={{ background: C.maroonSoft }}>
          <span style={{ color: C.maroon }}>ⓘ</span>
          <p className="text-[12px] leading-snug" style={{ color: C.gold }}>Select a table to place order or view current order.</p>
        </div>
      </div>
    </div>
  );
}

function MenuScreen({ go, tableId, cart, setQty }) {
  const [cat, setCat] = useState("Breakfast");
  const [q, setQ] = useState("");
  const tableCart = cart[tableId] || {};
  const items = MENU[cat].filter((i) => i.name.toLowerCase().includes(q.toLowerCase()));
  const count = Object.values(tableCart).reduce((s, n) => s + n, 0);
  const total = Object.entries(tableCart).reduce((s, [id, n]) => s + n * ALL_ITEMS[id].price, 0);

  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: C.maroon }}>
        <StatusBar />
        <Header title={`Table ${tableId} - New Order`} onBack={() => go("tables")} />
        <div className="flex gap-1.5 px-4 pb-3 overflow-x-auto no-scrollbar">
          {CATEGORIES.map((c) => (
            <button
              key={c}
              onClick={() => setCat(c)}
              className="px-3.5 py-1.5 rounded-full text-[12.5px] font-medium whitespace-nowrap transition-colors"
              style={c === cat ? { background: "white", color: C.maroon } : { background: "rgba(255,255,255,0.18)", color: "white" }}
            >
              {c}
            </button>
          ))}
        </div>
      </div>

      <div className="px-4 pt-3">
        <div className="flex items-center gap-2 rounded-xl px-3.5 py-2.5" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
          <span className="text-[13px] flex-1" style={{ color: C.ink }}>{cat}</span>
          <ChevronDown size={14} color={C.inkSoft} />
          <div className="w-px h-4" style={{ background: C.line }} />
          <Search size={15} color={C.inkSoft} />
        </div>
      </div>

      <div className="flex-1 overflow-y-auto px-4 pt-3 pb-3 flex flex-col gap-2.5">
        {items.map((it) => (
          <div key={it.id} className="flex items-center gap-3 rounded-xl p-2.5" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
            <div className="w-11 h-11 rounded-lg flex items-center justify-center text-xl shrink-0" style={{ background: C.maroonSoft }}>{it.emoji}</div>
            <div className="flex-1 min-w-0">
              <p className="text-[13.5px] font-medium truncate" style={{ color: C.ink }}>{it.name}</p>
              <p className="text-[12px]" style={{ color: C.inkSoft }}>{it.priceNote ? it.priceNote : <Rupee n={it.price} />}</p>
            </div>
            <Stepper
              qty={tableCart[it.id] || 0}
              onDec={() => setQty(tableId, it.id, Math.max(0, (tableCart[it.id] || 0) - 1))}
              onInc={() => setQty(tableId, it.id, (tableCart[it.id] || 0) + 1)}
            />
          </div>
        ))}
      </div>

      {count > 0 && (
        <button onClick={() => go("bill")} className="mx-4 mb-4 rounded-xl px-4 py-3.5 flex items-center gap-2 text-white active:scale-[0.98] transition-transform" style={{ background: C.maroon }}>
          <ShoppingCart size={16} />
          <span className="text-[13px] font-medium">{count} item{count > 1 ? "s" : ""} &nbsp;|&nbsp; <Rupee n={total} /></span>
          <span className="ml-auto text-[13.5px] font-semibold">View Bill →</span>
        </button>
      )}
    </div>
  );
}

function BillScreen({ go, tableId, cart, setQty, payment, setPayment }) {
  const tableCart = cart[tableId] || {};
  const lines = Object.entries(tableCart).filter(([, n]) => n > 0).map(([id, n]) => ({ ...ALL_ITEMS[id], qty: n }));
  const subtotal = lines.reduce((s, l) => s + l.qty * l.price, 0);

  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: C.maroon }}>
        <StatusBar />
        <Header
          title={`Table ${tableId} - Bill`}
          onBack={() => go("menu")}
          right={
            <button onClick={() => lines.forEach((l) => setQty(tableId, l.id, 0))} className="text-[12px] flex items-center gap-1 text-white/85">
              🗑 Clear All
            </button>
          }
        />
      </div>

      <div className="flex-1 overflow-y-auto px-4 pt-4 pb-3">
        <div className="grid grid-cols-[1fr_auto_auto_auto] gap-2 text-[11px] font-semibold px-1 pb-2" style={{ color: C.inkSoft }}>
          <span>Item</span><span>Qty</span><span>Price</span><span className="text-right">Total</span>
        </div>
        <div className="flex flex-col gap-2 mb-3">
          {lines.map((l) => (
            <div key={l.id} className="grid grid-cols-[1fr_auto_auto_auto] gap-2 items-center rounded-xl px-3 py-2.5" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
              <span className="text-[13px] font-medium truncate" style={{ color: C.ink }}>{l.name}</span>
              <div className="flex items-center gap-1.5">
                <button onClick={() => setQty(tableId, l.id, Math.max(0, l.qty - 1))} className="w-5 h-5 rounded flex items-center justify-center" style={{ background: C.maroonSoft, color: C.maroon }}><Minus size={11} /></button>
                <span className="w-4 text-center text-[12.5px] font-semibold" style={{ color: C.ink }}>{l.qty}</span>
                <button onClick={() => setQty(tableId, l.id, l.qty + 1)} className="w-5 h-5 rounded flex items-center justify-center" style={{ background: C.maroonSoft, color: C.maroon }}><Plus size={11} /></button>
              </div>
              <span className="text-[12.5px]" style={{ color: C.inkSoft }}><Rupee n={l.price} /></span>
              <span className="text-[13px] font-semibold text-right" style={{ color: C.ink }}><Rupee n={l.qty * l.price} /></span>
            </div>
          ))}
        </div>

        <button onClick={() => go("menu")} className="w-full rounded-xl py-3 mb-5 text-[13px] font-medium flex items-center justify-center gap-2" style={{ border: `1.5px dashed ${C.maroon}`, color: C.maroon }}>
          <PlusCircle size={15} /> Add More Items
        </button>

        <div className="rounded-xl px-4 py-3.5 mb-4" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
          <Row label="Subtotal" value={<Rupee n={subtotal} />} />
          <Row label="CGST (0%)" value="₹0" />
          <Row label="SGST (0%)" value="₹0" />
          <div className="flex items-center justify-between pt-2 mt-1" style={{ borderTop: `1px solid ${C.line}` }}>
            <span className="text-[14px] font-bold" style={{ color: C.maroon }}>Total Amount</span>
            <span className="text-[16px] font-bold" style={{ color: C.maroon }}><Rupee n={subtotal} /></span>
          </div>
        </div>

        <p className="text-[13px] font-semibold mb-2" style={{ color: C.ink }}>Payment Method</p>
        <div className="grid grid-cols-3 gap-2.5 mb-1">
          {[["Cash", <Wallet size={15} />], ["UPI", <CreditCard size={15} />], ["Other", <MoreHorizontal size={15} />]].map(([m, icon]) => (
            <button
              key={m}
              onClick={() => setPayment(m)}
              className="flex flex-col items-center gap-1 py-3 rounded-xl text-[12px] font-medium transition-colors"
              style={payment === m ? { background: C.maroon, color: "white" } : { background: C.paper, border: `1px solid ${C.line}`, color: C.ink }}
            >
              {icon}{m}
            </button>
          ))}
        </div>
      </div>

      <button
        disabled={!lines.length || !payment}
        onClick={() => go("preview")}
        className="mx-4 mb-4 rounded-xl py-3.5 text-white text-[14px] font-semibold disabled:opacity-40 active:scale-[0.98] transition-transform"
        style={{ background: C.maroon }}
      >
        Generate Bill →
      </button>
    </div>
  );
}

function Row({ label, value }) {
  return (
    <div className="flex items-center justify-between py-1">
      <span className="text-[13px]" style={{ color: C.inkSoft }}>{label}</span>
      <span className="text-[13px]" style={{ color: C.ink }}>{value}</span>
    </div>
  );
}

function PreviewScreen({ go, tableId, cart, payment, billNo, saveBill }) {
  const tableCart = cart[tableId] || {};
  const lines = Object.entries(tableCart).filter(([, n]) => n > 0).map(([id, n]) => ({ ...ALL_ITEMS[id], qty: n }));
  const total = lines.reduce((s, l) => s + l.qty * l.price, 0);
  const now = new Date();
  const dateStr = "15 Sep 2026";
  const timeStr = now.toLocaleTimeString("en-IN", { hour: "2-digit", minute: "2-digit" });

  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: C.maroon }}>
        <StatusBar />
        <Header title="Bill Preview" onBack={() => go("bill")} />
      </div>

      <div className="flex-1 overflow-y-auto px-4 pt-4 pb-3">
        <div className="rounded-2xl p-5" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
          <div className="flex flex-col items-center text-center mb-3">
            <div className="w-12 h-12 rounded-full flex items-center justify-center mb-1.5" style={{ background: C.maroonSoft }}>
              <ChefHat size={22} color={C.maroon} />
            </div>
            <p className="text-[10px]" style={{ color: C.inkSoft }}>होटेल</p>
            <p className="text-[15px] font-bold" style={{ color: C.maroon }}>GANESH</p>
            <p className="text-[10px]" style={{ color: C.inkSoft }}>प्युअर व्हेज • PURE VEG</p>
            <p className="text-[9.5px] mt-1" style={{ color: C.inkSoft }}>AAVAD TUMCHI, CHAAV AAMCHI</p>
          </div>
          <div className="border-t border-dashed my-3" style={{ borderColor: C.line }} />
          <Row label="Bill No" value={billNo} />
          <Row label="Date" value={dateStr} />
          <Row label="Time" value={timeStr} />
          <Row label="Table No" value={tableId} />
          <div className="border-t border-dashed my-3" style={{ borderColor: C.line }} />
          <div className="grid grid-cols-[1fr_auto_auto_auto] gap-2 text-[10.5px] font-semibold pb-1.5" style={{ color: C.inkSoft }}>
            <span>Item</span><span>Qty</span><span>Rate</span><span className="text-right">Amt</span>
          </div>
          {lines.map((l) => (
            <div key={l.id} className="grid grid-cols-[1fr_auto_auto_auto] gap-2 py-1 text-[12.5px]" style={{ color: C.ink }}>
              <span className="truncate">{l.name}</span><span>{l.qty}</span><span><Rupee n={l.price} /></span>
              <span className="text-right font-medium"><Rupee n={l.qty * l.price} /></span>
            </div>
          ))}
          <div className="border-t border-dashed my-3" style={{ borderColor: C.line }} />
          <div className="flex items-center justify-between">
            <span className="text-[14px] font-bold" style={{ color: C.maroon }}>Total Amount</span>
            <span className="text-[16px] font-bold" style={{ color: C.maroon }}><Rupee n={total} /></span>
          </div>
          <Row label="Payment Method" value={payment} />
          <div className="text-center mt-4">
            <p className="italic text-[14px]" style={{ fontFamily: "'Playfair Display', serif", color: C.gold }}>Thank You!</p>
            <p className="italic text-[14px]" style={{ fontFamily: "'Playfair Display', serif", color: C.gold }}>Visit Again.</p>
          </div>
        </div>
      </div>

      <div className="flex gap-3 px-4 mb-4">
        <button className="flex-1 rounded-xl py-3.5 text-[13.5px] font-semibold flex items-center justify-center gap-2 active:scale-[0.98] transition-transform" style={{ background: C.paper, border: `1.5px solid ${C.maroon}`, color: C.maroon }}>
          <Printer size={16} /> Print Bill
        </button>
        <button onClick={saveBill} className="flex-1 rounded-xl py-3.5 text-[13.5px] font-semibold text-white flex items-center justify-center gap-2 active:scale-[0.98] transition-transform" style={{ background: C.maroon }}>
          <Save size={16} /> Save Bill
        </button>
      </div>
    </div>
  );
}

function SavedScreen({ go, lastBill }) {
  return (
    <div className="flex flex-col h-full" style={{ background: C.cream }}>
      <div style={{ background: C.maroon }}>
        <StatusBar />
        <Header title="Bill Saved" menu />
      </div>
      <div className="flex-1 flex flex-col items-center px-6 pt-10">
        <div className="w-24 h-24 rounded-full flex items-center justify-center mb-5" style={{ background: "#E8F6EC" }}>
          <CheckCircle2 size={52} color="#2E9E4F" strokeWidth={1.7} />
        </div>
        <h2 className="text-[19px] font-bold mb-1.5" style={{ color: C.ink }}>Bill Saved Successfully!</h2>
        <p className="text-[13px] mb-8 text-center" style={{ color: C.inkSoft }}>
          Bill No. <span className="font-semibold" style={{ color: C.ink }}>{lastBill?.billNo}</span> has been saved.
        </p>

        <div className="w-full flex flex-col gap-3">
          <button onClick={() => go("dashboard")} className="w-full flex items-center gap-3 px-4 py-3.5 rounded-xl active:scale-[0.98] transition-transform" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
            <Receipt size={16} color={C.maroon} />
            <span className="text-[13.5px] font-medium flex-1 text-left" style={{ color: C.ink }}>View Today's Bills</span>
            <ArrowLeft size={14} className="rotate-180 opacity-40" />
          </button>
          <button onClick={() => go("dashboard")} className="w-full flex items-center gap-3 px-4 py-3.5 rounded-xl active:scale-[0.98] transition-transform" style={{ background: C.paper, border: `1px solid ${C.line}` }}>
            <History size={16} color={C.maroon} />
            <span className="text-[13.5px] font-medium flex-1 text-left" style={{ color: C.ink }}>View Bill History</span>
            <ArrowLeft size={14} className="rotate-180 opacity-40" />
          </button>
          <button onClick={() => go("tables")} className="w-full flex items-center justify-center gap-2 px-4 py-3.5 rounded-xl text-white active:scale-[0.98] transition-transform" style={{ background: C.maroon }}>
            <PlusCircle size={16} /> <span className="text-[13.5px] font-semibold">New Order</span>
          </button>
        </div>
      </div>
    </div>
  );
}

/* ---------------------------------- APP ------------------------------------ */
export default function App() {
  const [screen, setScreen] = useState("home");
  const [selectedTable, setSelectedTable] = useState(1);
  const [cart, setCart] = useState({});
  const [payment, setPayment] = useState(null);
  const [savedBills, setSavedBills] = useState([]);
  const [lastBill, setLastBill] = useState(null);

  const setQty = (tableId, itemId, qty) => {
    setCart((prev) => ({ ...prev, [tableId]: { ...(prev[tableId] || {}), [itemId]: qty } }));
  };

  const go = (s) => setScreen(s);
  const selectTable = (t) => { setSelectedTable(t); setPayment(null); };

  const saveBill = () => {
    const tableCart = cart[selectedTable] || {};
    const lines = Object.entries(tableCart).filter(([, n]) => n > 0).map(([id, n]) => ({ ...ALL_ITEMS[id], qty: n }));
    const total = lines.reduce((s, l) => s + l.qty * l.price, 0);
    const billNo = `HG-${(452 + savedBills.length).toString().padStart(5, "0")}`;
    const bill = { billNo, table: selectedTable, total, payment, lines };
    setSavedBills((prev) => [...prev, bill]);
    setLastBill(bill);
    setCart((prev) => ({ ...prev, [selectedTable]: {} }));
    setPayment(null);
    setScreen("saved");
  };

  const billNoPreview = `HG-${(452 + savedBills.length).toString().padStart(5, "0")}`;

  const screenMap = {
    home: <HomeScreen go={go} />,
    dashboard: <DashboardScreen go={go} savedBills={savedBills} cart={cart} />,
    tables: <TablesScreen go={go} cart={cart} selectTable={selectTable} />,
    menu: <MenuScreen go={go} tableId={selectedTable} cart={cart} setQty={setQty} />,
    bill: <BillScreen go={go} tableId={selectedTable} cart={cart} setQty={setQty} payment={payment} setPayment={setPayment} />,
    preview: <PreviewScreen go={go} tableId={selectedTable} cart={cart} payment={payment} billNo={billNoPreview} saveBill={saveBill} />,
    saved: <SavedScreen go={go} lastBill={lastBill} />,
  };

  return (
    <div className="w-full min-h-screen flex items-center justify-center py-8" style={{ background: "#EDE3DD", fontFamily: "'Poppins', sans-serif" }}>
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Playfair+Display:ital@1&display=swap');
        .no-scrollbar::-webkit-scrollbar{display:none}
        .no-scrollbar{-ms-overflow-style:none;scrollbar-width:none}
      `}</style>
      <div
        className="relative overflow-hidden flex flex-col"
        style={{
          width: 390, height: 800, borderRadius: 44, background: C.cream,
          boxShadow: "0 30px 60px rgba(0,0,0,0.35), 0 0 0 10px #1a1a1a, 0 0 0 12px #333",
        }}
      >
        {screenMap[screen]}
      </div>
    </div>
  );
}
